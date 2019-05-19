<template>
  <div class="prue">
    <h6>desarrollado por {{ msg }}</h6>
	<h6>codigo disponible en <a url="">github</a></h6>
	
  </div>
</template>

<script>
export default {
  name: 'foo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div{
background-color: black;
color:white;
}
</style>
