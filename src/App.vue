<template>
  <div id="app">
    <myName 
    :name ="name"/>
    
  </div>
</template>

<script>

import myName from './components/myName.vue'


export default {
  name: 'App',
  components: {
    myName
  },
  data () {
    return {
      name: 'Barnabas Asha'
    }
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
