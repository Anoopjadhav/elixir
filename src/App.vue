
<template>
  <div id="app">
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

<hello-world></hello-world>



  </div>
</template>
<script>
 /* eslint-disable */ 
import particleJs from "../node_modules/particlesjs/dist/particles.min.js"
import HelloWorld from './components/LoginPage.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
input,
#app {
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
}


.particles-js-canvas-el{
position:absolute;  
display:block;
top:0;  
left:0;  
z-index:-1;
background-image:url('./assets/aurora.jpg');
background-size: cover;
}
input{
  background: none;
  box-shadow: none;
  border:1px solid white;
  height:2.5rem;
  padding:0 1rem;
  font-size:1rem;
  text-align: left;
}
::-webkit-input-placeholder,
::-moz-placeholder,
::-ms-input-placeholder,
::-moz-placeholder{
  color:rgba(255,255,255,0.8);
}
input + input{
  margin-top: 2rem;
}
</style>
