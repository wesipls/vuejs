<template>
	<div id="app">
		<SideBar/>
		<div id=maincontent>
			<intro/>
			<experience/>
			<education/>
			<bottomtext/>
		</div>
	</div>
</template>

<script>
import SideBar from './components/sidebar.vue'
import intro from './components/intro.vue'
import experience from './components/experience.vue'
import education from './components/education.vue'
import bottomtext from './components/footer.vue'

export default {
	name: 'App',
	components: {
	SideBar,
	intro,
	experience,
	education,
	bottomtext
	}
}
</script>


<style>
body {
	background-color: #DCDCDC;
	font-family: 'Open Sans Condensed', sans-serif;
}
#app {
	background-color: white;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	width: 1200px;
	display: flex;
	margin: 0 auto;
}
#maincontent {
	flex: 1;
}
#pagetitle {
	border: solid 2px #00A896;
	width: 250px;
	font-size: 25px;
	margin-left: 50px;
}

</style>
