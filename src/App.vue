<template>
<div id="webgame">
<router-view/>
</div>
</template>
 
<script>
export default {
  name: 'App'  
}  
</script>

<style>
  *{
    padding: 0px;
    margin: 0px;
  }
  #webgame{
    height: 100vh;
    width: 100vw;
  }
</style>
