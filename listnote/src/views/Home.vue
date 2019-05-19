<template>
  <div class="home">
	<prue msg="isidro lucena santiago"/>
	<foo msg="isidro lucena santiago"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import prue from '@/components/prue.vue'
import foo from '@/components/foo.vue'

export default {
  name: 'home',
  components: {
    prue
	,foo
  }
}
</script>

