<template>
    <div class="content-container">
        <button class="content-button">{{ content }}</button>
    </div>
</template>

<script>
export default {
  name: 'Content',
  props: {
    content: String
  }
}
</script>

<style>
  .content-container {
      width:100vw;
      height:80vh;
      background-color: white;
  }
</style>
