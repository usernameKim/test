<template>
  <div id="app">
    <empList></empList>
  </div>
</template>

<script>
import empList from './components/empList.vue'

export default {
  name: 'App',
  components: {
    empList
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
