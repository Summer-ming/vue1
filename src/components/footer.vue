<template id='footer'>
	<div>
		<h1>两条平行线永远不想交</h1>
		<div class='mm'>曾经有一份真挚的感情摆在我的面前我没有珍惜，等我失去的时候才追悔莫及，人间最痛苦的事莫过于此，你的剑在我的咽喉上刺下去吧，不用在犹豫了！如果上天能给我一次再来一次的机会，我会对哪个女孩说三个字：我爱你，如果非要在这份爱上加一个期限，我希望是一万年！</div>
	<v-child></v-child>
	</div>
	
</template>

<script>
	import child from './child.vue'
	var footer={
		template:"#footer"
	}
	/*module.exports=footer*/
	export default {
 components:{
  	
  	'v-child':child
  }
}
</script>

<style>
	.mm{
		width:600px;white-space: wrap;text-overflow: ellipsis;overflow:hidden;margin:auto;
	}
	.mm:hover{
		color:red
	}
</style>