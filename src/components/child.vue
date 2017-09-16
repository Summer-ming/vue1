<template>
	<div id="child">
		<h3>我是子组件你好啊</h3>
		<h4>今天天气很好适合出去嘿嘿</h4>
		<button @click='tab'>我是你哥哥</button>
	</div>
</template>

<script>
	var child={
		template:'#child',
		methods:{
			tab:function(){
				alert('你好。。美女')
			}
		}
	}
	module.exports=child
</script>

<style>
	
</style>