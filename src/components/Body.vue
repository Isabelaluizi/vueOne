<template>
    <div id="body-container">
        <h1> {{ content }}</h1>
    </div>
</template>

<script>
export default {
  name: 'Body',
 
  props: {
    content: String
  }
}
</script>

<style scoped>
  #body-container {
      width:100vw;
      height:80vh;
  }
</style>
