<template>
  <header>
    <NavBar/>
  </header>
  
  <MainCard/>
  <ProjectsCard/>
</template>

<script>

import NavBar from './components/NavBar.vue';
import MainCard from './components/MainCard.vue'
import ProjectsCard from './components/ProjectsCard.vue';


export default {
  name: 'App',
  components: {
    NavBar,
    MainCard,
    ProjectsCard
  }
}
</script>

<style>
body{
  margin: 0;
}
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #395144;
  background-color: #F0EBCE;
  padding-bottom: 10;
}
</style>
