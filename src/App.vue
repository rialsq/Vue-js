<template>
<div id="app">
    <todo/>
  </div>
</template>

<script>
import Vue from 'vue'
import VueMaterial from 'vue-material'
import 'vue-material/dist/vue-material.min.css'
import 'materialize-css/sass/materialize.scss';
// eslint-disable-next-line
import 'materialize-css/dist/js/materialize.min.js';

Vue.use(VueMaterial)
import todo from './components/todo.vue'
export default {
  name: 'app',
  components: {
    todo
  }
}
</script>

<style>
#app {
  margin: 0 auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: cornflowerblue;
}
</style>
