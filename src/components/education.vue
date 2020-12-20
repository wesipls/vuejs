<template>
	<div id="edu">
		<div style="width:950px; float: left;"><h1 id="pagetitle">Education</h1><div style="border-bottom: solid 2px #00A896; margin-left: 352px; margin-top: -40px;"></div></div>
		<div id="timelineleft">
			<p style="margin-top: -17px;">2020</p>
			<p style="margin-top: 174px;" >2013</p>
		</div>
		<div id="timeline2">
		</div>
		<div id="timelineright">
			<div  style="margin-top: -40px;" id="timelinedot"></div>
			<h3 id="jobinfo">Full Stack engineering courses</h3>
			<h4 id="subtitle">Opiframe</h4>
			<h4 id="jobdate">04/2020 - 10/2020</h4>
			<ul id="joblist">
				<li class="a">Focused on React.js, node.js and MongoDB</li>
				<li class="a">Addition courses in Redux, Angular.js, Vue.js and MySQL</li>
				<li class="a">Introduction to pentesting and software security</li>
			</ul>
			<div style="margin-top: 53px;" id="timelinedot"></div>
			<h3 style="margin-top: 50px;" id="jobinfo">Bachelor of Business Administration</h3>
			<h4 id="subtitle">Laurea UAS / Business Information Technology</h4>
			<h4 id="jobdate">08/2013 - 12/2016</h4>
			<ul id="joblist">
				<li class="a">International Degree</li>
				<li class="a">Personal focus on System Administration, networking and development</li>
				<li class="a">Thesis written on Network Automation, found <a href="https://www.theseus.fi/bitstream/handle/10024/120959/Thesis.pdf?sequence=1&isAllowed=y">here</a></li>
			</ul>
		</div>
	</div>
</template>
<script>
export default {
	name: 'experience',
	props: {
	}
}
</script>
<style scoped>
#edu {
	font-family: 'Open Sans Condensed', sans-serif;
}
#timeline2 {
	width: 3px;
	height: 380px;
	background-color: #00A896;
	float: left;
	margin-top: 60px;
}
</style>
