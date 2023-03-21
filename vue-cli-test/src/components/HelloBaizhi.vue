<template>
  <p>hello {{content}}</p>
</template>

<script>
  export default {
    name: 'HelloBaizhi',
    data() {
      return {
        content: "baizhi"
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  p {
    font-size: 2em;
    text-align: center;
    color: yellow;
  }
</style>
