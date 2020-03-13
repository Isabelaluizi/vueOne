<template>
    <div class="header-container">
        <h3 class="header-content">{{ content }}</h3>
    </div>
</template>

<script>
export default {
  name: 'Header',

  props: {
    content: String
  }
}
</script>

<style scoped>
  .header-container {
    width: 100vw;
    height: 20vh;
    background-color: cornflowerblue;
    margin:0;
    padding:0;
  }

</style>