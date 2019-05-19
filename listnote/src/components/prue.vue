<template>
  <div>
    <h1>proyecto vue :{{ msg }}</h1>
	<input type="text" value="prueba"></input>
	<button v-on:click="addtodo">pulsame</button>
	<h6></h6>
	<item title="prueba"></item>
	
  </div>
</template>

<script>
import item from '@/components/item.vue'
export default {
  name: 'prue',
  components:{
  item
  }
  ,props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div{
	background-color:black;
	color:white;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
