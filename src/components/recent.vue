<template>
	<div id="recent">
	<h1>Recent Work Projects</h1>
	<div id="left">
	<p>Customer website migration</p>
	<p>	- lol</p>
	<p>Customer website optimization</p>
	<p>Customer website deloyment</p>
	</div>
	<div id="right">
	<p>tech: trafficserver, Wordpress, nginx, bind, Lets Encrypt</p>
	<p>tech: PHP, Silverstripe, Memcache, trafficserver, apache2</p>
	<p>tech: Vue.js, trafficserver, bind, docker, docker-compose, nginx, js</p>
	</div>
	</div>
</template>

<script>

export default {
	name: 'recent'
}
</script>
<style scoped>

#left {
	float: left;
	width: 480px;
}
#right {
	float: right;
	width: 480px;
}
</style>
