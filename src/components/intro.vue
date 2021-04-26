<template>
	<div id="intro">
		<img id="face" src="../assets/face.png">
		<h1 id="title">Kim Valkama</h1>
		<div class="divider"></div>
		<h2 id="description">Sys Admin / DevOps Engineer</h2> 
		<a href="https://github.com/wesipls"><img class="icons" src="../assets/github.svg"></a>
		<a href="https://linkedin.com/in/kim-valkama"><img class="icons" src="../assets/linkedin.svg"></a>
		<a href="cv.pdf"><p id="cvlink">CV</p></a>
		<p style="margin-left: -528px;" class="information">E-mail: <a href="mailto:kim.valkama@pm.me"> kim.valkama@protonmail.com</a></p>
		<p style="margin-left: -228px;" class="information">Phone: +358 (0)44 595 9906</p>
		<p class="information">Location: Espoo, 02750, FIN</p>
		<h3>What I do.</h3>
		<p id="breadtext">Jack of all trade in IT. Current day-to-day work includes a wide variety of tasks including; server management, customer hosting solutions, service migrations and deployments, supporting developers with virtualization solutions and development environments. Enjoy helping co-workers with IT issues and teaching junior developers the basics of programming.</p>
		<h4>How I do it.</h4>
		<p id="breadtext">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
	</div>
</template>

<script>

export default {
	name: 'intro'
}
</script>
<style scoped>
#intro {
	margin-top: 50px;
}
h1 {
	font-size: 50px;
	margin-bottom: 10px;
}
h2 {
	font-style: italic;
	margin-top: 10px;
	float: left;
	margin-right: 30px;
}
h3 {
	margin-top: 100px;
	font-size: 25px;
}
h4 {
	font-size: 25px;
}
.icons {
	float: left;
	margin-top: 13px;
	margin-left: 25px;
}
#cvlink {
	font-style: italic;
	font-weight: bold;
	font-size: 26px;
	margin-left: 20px;
	float: left;
	margin-top: 9px;
}
a {
	text-decoration: none;
	color: black;
}
#face {
        height: 99px;
        width: 90px;
	float: left;
	margin-right: 20px;
	margin-top: 10px;
}
.divider {
	width: 320px;
	margin-left: 110px;
	height: 3px;
	background-color: black;
}
.information {
	margin-top: 45px;
	float: left;
}
#breadtext {
	margin-top: 20px;
	font-size: 18px;
}
</style>
