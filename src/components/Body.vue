<template>
    <div id="body-container">
      <BodyOne content="Click here"/>
      <BodyTwo content="This is body part two"/>
      <BodyThree content="This is body part three"/>
        
    </div>
</template>

<script>
import BodyOne from './BodyOne.vue'
import BodyTwo from './BodyTwo.vue'
import BodyThree from './BodyThree.vue'

export default {
  name: 'Body',
   components: {
    BodyOne,
    BodyTwo,
    BodyThree
  }
  
}

</script>


