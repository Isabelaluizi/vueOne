<template>
    <div class="footer-container">
        <h3 class="footer-content">{{ content }}</h3>
    </div>
</template>

<script>
export default {
  name: 'Footer',
 
  props: {
    content: String
  }
}
</script>

<style scoped>
  .footer-container {
    width: 100vw;
    height: 20vh;
    background-color: cornflowerblue;
    margin:0;
    padding:0;
  }

</style>