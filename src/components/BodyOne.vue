<template>
    <div id="bodyOne-container">
        <h1 v-on:click="changeColor" id="bodyOne-click"> {{ content }}</h1>
    </div>
</template>

<script>

export default {
  name: 'BodyOne',
  props: {
    content: String
  },
  methods: {
      changeColor: function() {
          document.getElementById("bodyOne-container").style.backgroundColor = "red";
      } 
  }
}
</script>

<style scoped>
  #bodyOne-container {
      width:100vw;
      height:40vh;
      border: 1px solid black;
  }
  #bodyOne-click {
      border: 1px solid black;
      margin-top: 5vh;
      margin-left: 25vw;
      width:50vw;
      padding: 5px;
  }

</style>