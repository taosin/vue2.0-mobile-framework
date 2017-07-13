<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'index',
    data () {
      return {
        msg: 'Hello, world!'
      }
    }
  }
</script>

<style scoped>
  .hello {
    text-align: center;
  }
</style>
