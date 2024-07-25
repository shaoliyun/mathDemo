<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!-- <katex-element expression="\\ \mathcal{P} = (t,\mathbf{G}')"/> -->
    <MathType></MathType>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import MathType from './components/mathType.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MathType
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

@import "../node_modules/katex/dist/katex.min.css";

.katex-html {
  display: none;
}

</style>
