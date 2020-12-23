<template>
	<div id="info">
	<img id="face" src="../assets/face.png">
		<div class="statcontainer">
			<img class="imgs" src="../assets/phone-line.png">
			<h3 class="breadtext">+358 (0)44 595 9906</h3>
		</div>
		<div class="statcontainer">
			<img class="imgs" style="margin-top:7px;" src="../assets/envelope-line.png">
			<h3 class="breadtext"><a href="mailto:kim.valkama@pm.me" style="text-decoration: none; color: white;">kim.valkama@pm.me</a></h3>
		</div>
		<div class="statcontainer">
			<img class="imgs" src="../assets/home-location.png">
			<h3 class="breadtext">Espoo 02750, FI</h3>
		</div>
		<div id="linkbox">
			<a href="https://github.com/wesipls"><img class="botimg" style="width:45px;height:45px;" src="../assets/github.png"></a>
			<a href="https://fi.linkedin.com/in/kim-valkama"><img class="botimg" style="width:40px;height:40px;padding-top:4px;" src="../assets/linkedin.png"></a>
			<a href="https://www.cycleit.fi/portfolio/KimCV.pdf"><img class="botimg" style="width:40px;height:40px;padding-top:4px;" src="../assets/pdf-files.png"></a>
		</div>
		<div class="langbox">
			<h4 class="sidetitle">Language Skills:</h4>
			<div class="langcontainer"><p class="langdescription">Finnish</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div></div></div>
			<div class="langcontainer"><p class="langdescription">English</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Swedish</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div></div></div>
			<div class="langcontainer"><p class="langdescription">German</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div><div class="n"></div></div></div>
		</div>
		<div class="langbox">
			<h4 class="sidetitle">Administration Skills:</h4>
			<div class="langcontainer"><p class="langdescription">Linux</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Windows</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Mac</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Virtualization</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Networking</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">AWS</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div></div></div>
		</div>
		<div class="langbox">
			<h4 class="sidetitle">Development Skills:</h4>
			<div class="langcontainer"><p class="langdescription">Bash</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Python</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">HTML/CSS</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Javascript</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div><div class="n"></div></div></div>
			<div class="langcontainer"><p class="langdescription">Vue.js</p><div class="statbox"><div class="p"></div><div class="p"></div><div class="p"></div><div class="n"></div><div class="n"></div></div></div>
		</div>
		<div id="passions">
			<h4 id="passiontitle">Passions:</h4>
			<img class="imgs" src="../assets/cmd-terminal.png">
			<p class="passiontext">Opensource Technology</p>
			<img class="imgs" src="../assets/gym-dumbbell.png">
			<p class="passiontext">Diverse Excersice</p>
			<img class="imgs" src="../assets/paw.png">
			<p class="passiontext">Animals and Ecosystems</p>
		</div>
	</div>
</template>

<script>
export default {
	name: 'SideBar',
	props: {
	}
}
</script>

<style>
#info {
	color: white;
	flex: 1;
	background-color: #05668d;
	width: 250px;
}
#face {
	height: 198px;
	width: 181px;
	margin-top: 40px;
}
.statcontainer {
	margin-top: 30px;
}
.imgs {
	margin-left: 20px;
	float: left;
}
.breadtext {
	font-size: 20px;
}
#linkbox {
	margin-top:20px;
}
.botimg {
	float: left;
	margin-top: 30px;
	margin-left: 20px;
	margin-right: 20px;
}
.langbox {
	margin-top: 20px;
	float: left;
	text-align: center;
}
.sidetitle {
	font-size: 20px;
}
.langcontainer {
	width: 250px;
	float: left;
}
.langdescription {
	font-size: 20px;
	margin-top: 0px;
	margin-bottom: 5px;
	margin-left: 30px;
	float: left;
}
.statbox {
	float: right;
	margin-right: 30px;
}
.p {
	background-color: white;
	width: 15px;
	height: 15px;
	margin-top: 7px;
	margin-left: 5px;
	float: left;
}
.n {
	background-color: #028090;
	width: 15px;
	height: 15px;
	float: left;
	margin-top: 7px;
	margin-left: 5px;
}
#passions {
	width: 250px;
	float: left;
	margin-top: 50px;
	text-align: center;
}
#passiontitle {
	font-size: 20px;
}
.passiontext {
	font-size: 20px;
}
</style>
