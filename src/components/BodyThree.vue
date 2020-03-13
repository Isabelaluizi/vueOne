<template>
    <div id="bodyThree-container">
        <h1> {{ content }}</h1>
    </div>
</template>

<script>

export default {
  name: 'BodyThree',
  props: {
    content: String
  }
}
</script>

<style scoped>
  #bodyThree-container {
      width:100vw;
      height:40vh;
      border: 1px solid black;
  }
</style>