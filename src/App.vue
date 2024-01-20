<script>

  export default {
    name: 'App',
      data() {
        return {
          message: 'Hello, World!',
          link: 'https://picsum.photos/200/300'
      }
    }
  }
</script>

<template>
  <div>
    <h1>{{ message }}</h1>
    <img :src='link' alt="random picture">
  </div>

</template>

<style>

</style>
