<template>
  <div id="container">
    <h3>You must <span class="log-in">Log in</span></h3>
    <Login />
  </div>
</template>

<script>
import Login from './components/Login.vue';
export default {
  name: 'App',
  components: { Login },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  margin-top: 60px;
}

#container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}
</style>
