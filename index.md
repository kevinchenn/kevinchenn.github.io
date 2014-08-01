---
layout: default
permalink: /
title: "Home"
---
<div class="page-lead" style="background-image:url(http://31.media.tumblr.com/b92879483bd60c7db0871cc64b694b05/tumblr_n9hyqfJavs1st5lhmo1_1280.jpg)">
	<div class="wrap page-lead-content">
		<h1>Hi, I'm Kevin!</h1>
		<h3 style="font-style:italic;">I got a dollar and a dream.</h3>
	</div>
</div>
<!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div>
<!-- /.tiles -->