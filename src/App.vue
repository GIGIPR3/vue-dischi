<template>
  <div id="app">


    <NavBar />

    <DischiArea />

  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import DischiArea from './components/DischiArea.vue'
/* import axios from 'axios'; */

export default {
  name: 'App',
  components: {
    NavBar,
    DischiArea
  }
}
</script>

<style lang="scss">

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
