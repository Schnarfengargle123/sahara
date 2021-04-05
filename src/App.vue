<template>
  <Dashboard />
  <!-- <Login /> -->
</template>

<script>
// import Login from './pages/Login';
import Dashboard from './pages/Dashboard';

export default {
  name: 'App',
  components: {
    // Login, 
    Dashboard
  }
}
</script>

<style>
* {
  margin: 0;
}

body {
  background-color: snow;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-family: 'Quicksand', sans-serif;
}

.logo {
  width: 12rem;
  height: 12rem;
  border-radius: 7rem;
  border: solid 0.15rem #465d75;
  box-shadow: 0.0rem 0.1rem 0.2rem 0.1rem slategray;
}

</style>
