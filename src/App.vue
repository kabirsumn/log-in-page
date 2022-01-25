<template>
  <div id="container">
    <h2>You must <span class="log-in" @click="getLogin">Log in</span></h2>
    <Login v-if="showLogin" @close="showLogin = false" />
  </div>
</template>

<script>
import Login from './components/Login.vue';
export default {
  name: 'App',
  components: { Login },
  data() {
    return {
      showLogin: false,
    };
  },

  methods: {
    getLogin() {
      this.showLogin = true;
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}

.log-in {
  color: #45e989;
  cursor: pointer;
  font-weight: 550;
  font-style: italic;
}
</style>
