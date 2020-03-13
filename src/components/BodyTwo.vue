<template>
    <div id="bodyTwo-container">
        <h1> {{ content }}</h1>
    </div>
</template>

<script>

export default {
  name: 'BodyTwo',
  props: {
    content: String
  }
}
</script>

<style scoped>
  #bodyTwo-container {
      width:100vw;
      height:40vh;
      border: 1px solid black;
  }
</style>