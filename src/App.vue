<template>
	<div id="app">
			<intro/>
			<recent/>
	</div>
</template>

<script>
import intro from './components/intro.vue'
import recent from './components/recent.vue'
export default {
	name: 'App',
	components: {
	intro,
	recent,
	}
}
</script>


<style>
body {
	font-family: 'Jura', sans-serif;
}
#app {
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	width: 960px;
	margin: 0 auto;
}
</style>
