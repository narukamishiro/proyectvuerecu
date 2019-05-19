<template>
  <li>
	<img></img>
    <h1>{{ title }}</h1>
	<h6>prioridad: </h6>
	<checkbox id="bj" value="baja" checked>  baja  </checkbox>
	<checkbox id= "md" value="media">  media  </checkbox>
	<checkbox id="lt"value="alta">  alta  </checkbox>
	<h6>  añadido hace </h6>
  </li>
</template>

<script>
export default {
  name: 'item',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
li{
	background-color:black;
	color:white;
}
h6{
	display: inline-block;
}
#bj{
	background-color:blue;
}
#md{
	background-color:green;
}
#lt{
	background-color:red;
}
</style>
