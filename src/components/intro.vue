<template>
	<div id="intro">
		<div style="height: 20px;"></div>
		<h1 id="introtitle">CV - RESUME</h1>
		<h1 id="title">Kim Valkama</h1>
		<h2 id="description">System Administrator / DevOps Engineer / Bachelor of BA</h2>
		<div style="width:950px; float: left;"><h1 id="pagetitle">Introduction</h1><div style="border-bottom: solid 2px #00A896; margin-left: 352px; margin-top: -40px;"></div></div>
		<p id="text">
Senior System administrator, junior developer and future DevOps expert. Anything "impossible to develop" is just a challenge. Will strive for automating my task so that I can focus on automating my next task. Prefers remote work unless I'm responsible for keeping the local network working. Started off my career maintaining Mac and windows, nowadays prefer working with Linux. Opensource enthusiast, want to learn Assembly programming one day.
		</p>
	</div>
</template>

<script>

export default {
	name: 'intro'
}
</script>

<style>
#introtitle {
  background-color: #028090;
  color: white;
  padding-top: 5px;
  padding-bottom: 5px;
  font-size: 15px;
  padding-left: 50px;
  text-align: left;
}

#title {
  font-size: 60px;
  margin-bottom: -10px;
}
#description {
  margin-top: 0px;
  font-style: italic;
  font-size: 25px;
}
#text {
  margin-top: 100px;
  font-size: 20px;
  text-align: left;
  padding-left: 70px;
  padding-right: 70px;
}
</style>
