<template>
  <div id="app">


    <NavBar />


  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style lang="scss" scoped>

* {
  font-family: 'Roboto Condensed', sans-serif;
  margin: 0%;
  padding: 0;
  box-sizing: border-box;
}



#app {
  height: 100vh;
  background-color: rgb(30, 45, 59);
}


</style>
