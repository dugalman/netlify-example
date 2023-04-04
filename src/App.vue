<template>
  <div id="app">
    {{greeting}}
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data(){
    return{
      greeting : 'Netlify is great!'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 30px;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
