<template>
  <div class="hello">
    <imgs/>
    <question/>
    <options/>
    
  </div>
</template>

<script>
import options from "./option.vue";
import question  from "./question.vue";
import imgs from "./imgs.vue";

export default {
  name: 'HelloWorld',
  components: {
    question,
    options,
    imgs
  },
  data () {
      
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
