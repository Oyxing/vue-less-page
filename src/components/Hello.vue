<template>
  <div class="hello">
	<h2> 大家好</h2>
	<div class="navbar">
		<ul class="navbar-ul">
			<li>你好</li>
			<li>你好1</li>
			<li>你好2</li>
			<li>你好3</li>
			<li>你好4</li>
		</ul>
	</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
	.hello{
		h2 {
			color:#0c0c0c
		}
	}


</style>
