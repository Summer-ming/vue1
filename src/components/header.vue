<template id='header'>
	<div>
		<h1 class='ming'>明明是一个夏天,却要想着过一个冬天</h1>
		<div class='box'>冬天来了春天还会远吗</div>
		<input type="text" v-model='str'/>
		<p>{{str}}</p>
	</div>
</template>
<script>
	var header={
		template:'#header',
		data:function(){
			return{
				str:''
			}
		}
	}
	module.exports=header
</script>
<style>
	.box{
		color:red;
	}
	p{color:blue}
	.ming{color:green}
</style>
