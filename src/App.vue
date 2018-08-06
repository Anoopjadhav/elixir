
<template>
  <div id="app">
    ELIXIR
    <vue-particles
        color="#79CEF6"
        :particleOpacity="0.7"
        :particlesNumber="90"
        shapeType="circle"
        :particleSize="2"
        linesColor="#FFFFFF"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
  </div>
</template>
<script>
 /* eslint-disable */ 
import particleJs from "../node_modules/particlesjs/dist/particles.min.js"
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.particles-js-canvas-el{
position:absolute;  
display:block;
top:0;  
left:0;  
z-index:0;
background-image:url('./assets/aurora.jpg');
background-size: cover;
}
</style>
