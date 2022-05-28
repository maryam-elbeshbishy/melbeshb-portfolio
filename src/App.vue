<template>
  <head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>

  <div class="topNav">
    <a href="#about">About Me</a>
    <a href="#current">Current Project</a>
    <a href="#project">Projects</a>
    <a href="#reach">Contact</a>
  </div>

  <div id="app">
    
  <div id="intro"> <IntroPage/> </div>

  <div id="about"> <AboutMe/> </div>

  <div id="current"> <CurrentPage/> </div>
  
  <div id="project"> <ProjectsPage/> </div>

  <div id="reach"> <ReachMe/> </div>

  </div>

</template>

<script>
import IntroPage from './components/Intro.vue';
import AboutMe from './components/AboutMe.vue';
import ProjectsPage from './components/Projects.vue';
import CurrentPage from './components/Current.vue';
import ReachMe from './components/ReachMe.vue';

export default {
  
  name: 'App',
  components: {
    IntroPage,
    AboutMe,
    ProjectsPage,
    CurrentPage,
    ReachMe,
}
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');
/* To make the divs not have white browser border */
html, body {
margin: 0;
padding: 0;
scroll-behavior: smooth;
}
.topNav{ 
  padding: 3vh;
  background-color: rgb(34,34,34);
  overflow: hidden;
}

/* General Layout */
#app {
  font-family: Nunito;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
header{
  padding: 3vw;
  background-color: rgb(34, 34, 34);
  color: white;
}
a{
  padding: 8vw;
  color:white;
  font-size: 1.2vw;
  text-decoration: none;
}
</style>
