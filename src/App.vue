<template>
  <div id="app">
    <input v-bind:id="inputId" type="text" v-model="message">
    {{ message }}
  </div>
</template>

<script>

export default {
  data(){
    return {
      inputId: 'abc',
      message: 'xin chao'
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
