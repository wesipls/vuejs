<template>
	<div id="xp">
		<div style="width:950px; float: left;"><h1 id="pagetitle">Experience</h1><div style="border-bottom: solid 2px #00A896; margin-left: 352px; margin-top: -40px;"></div></div>
		<div id="timelineleft">
			<p style="margin-top: -12px;">2020</p>
			<p style="margin-top: 172px;" >2019</p>
			<p style="margin-top: 385px;" >2017</p>
			<p style="margin-top: 167px;" >2013</p>
		</div>
		<div id="timeline">
		</div>
		<div id="timelineright">
			<div style="margin-top: -40px;" id="timelinedot"></div>
			<h3 id="jobinfo">DevOps System Administrator</h3>
			<h4 id="subtitle">Pharazon AB</h4>
			<h4 id="jobdate">05/2020 - Current</h4>
			<ul id="joblist">
				<li class="a">Development, deployment and maintenance of company servers</li>
				<li class="a">Device and service acquisition and integration</li>
				<li class="a">Responsible for System Administration and environment configuration</li>
			</ul>
			<div style="margin-top: 53px;" id="timelinedot"></div>
			<h3 style="margin-top: 50px;" id="jobinfo">Entrepreneur</h3>
			<h4 id="subtitle">CycleIT</h4>
			<h4 id="jobdate">02/2019 - 10/2020</h4>
			<ul id="joblist">
				<li class="a">Creation of company website and required services</li>
				<li class="a">Local and remote customer support for devices and services</li>
				<li class="a">Website update, optimization and migration</li>
			</ul>
			<h3 style="margin-top: 50px;" id="jobinfo">Webstore Maintenance/Technician</h3>
			<h4 id="subtitle">NT Data-Systems Oy</h4>
			<h4 id="jobdate">11/2019 - 03/2020</h4>
			<ul id="joblist">
				<li class="a">Maintenance of onsite store and webstore</li>
				<li class="a">Responsible of customer technical requests and customer orders</li>
				<li class="a">Responsible of hardware acquisitions</li>
			</ul>
			<div style="margin-top: 53px;" id="timelinedot"></div>
			<h3 style="margin-top: 50px;" id="jobinfo">Application Specialist</h3>
			<h4 id="subtitle">Retail Logistics Excellence -RELEX</h4>
			<h4 id="jobdate">05/2017 - 02/2019</h4>
			<ul id="joblist">
				<li class="a">Inhouse built java application maintenance</li>
				<li class="a">Application migration and load balancing</li>
				<li class="a">Server maintenance and network routing</li>
			</ul>
			<div style="margin-top: 53px;" id="timelinedot"></div>
			<h3 style="margin-top: 50px;" id="jobinfo">System administrator</h3>
			<h4 id="subtitle">Integral Oy</h4>
			<h4 id="jobdate">06/2013 - 01/2017</h4>
			<ul id="joblist">
				<li class="a">Supporting customer devices and services</li>
				<li class="a">Building and maintaining network environments</li>
				<li class="a">Automating network maintenance and updating</li>
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
<style>
#timelineleft {
	width: 150px;
	float: left;
	margin-top: 80px;
	font-size: 30px;
}
#timelinedot {
	width: 21px;
	height: 21px;
	background-color: white;
	border: solid 3px #00A896;
	border-radius: 100%;
	margin-top: 8px;
	margin-left: -62px;
	float:left;
}
#timeline {
	width: 3px;
	height: 1020px;
	background-color: #00A896;
	float: left;
	margin-top: 60px;
}
#timelineright {
	text-align: left;
	margin-left: 200px;
	padding-top: 150px;
}
#jobinfo {
	font-size: 25px;
	margin-top: -60px;
	margin-left: 30px;
	margin-bottom: 0px;
}

#subtitle {
	font-style: italic;
	font-size: 20px;
	margin-left: 30px;
	margin-top: 0px;
}
#jobdate {
	float: right;
	font-style: italic;
	margin-top: -54px;
	margin-right: 110px;
	font-size: 20px;
}
#joblist {
	font-size: 20px;
	margin-top: -17px;
}
.a {
	margin-top: 3px;
}
</style>
