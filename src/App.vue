<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{aa}}</h1>
    <v-header></v-header>
    <v-footer></v-footer>
  </div>
</template>

<script>
	import header  from './components/header.vue'
	import footer from './components/footer.vue'
export default {
  name: 'app',
  data () {
    return {
      aa:"我是明明"
    }
  },components:{
  	'v-header':header,
  	'v-footer':footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h1, h2 {
  font-weight: normal;
}
</style>
