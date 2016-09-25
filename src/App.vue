<template>
  <div id="app">
    <img src="./assets/logo.png"></img>
    <div class="normal-txt" id="text">{{ message }}</div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        message: 'Hello World!'
      }
    }
  }
</script>

<style>
  .normal-txt {
    font-family: Helvetica, sans-serif;
    font-size: 30px;
  }
</style>
