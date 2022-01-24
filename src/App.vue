<template>
  <div id="container">
    <h2>You must <span class="log-in">Log in</span></h2>
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
}

#container {
  height: 100vh;
  background-color: #e0dada;
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
