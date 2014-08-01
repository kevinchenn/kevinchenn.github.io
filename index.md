---
layout: default
permalink: /
title: "Home"
---
<div class="page-lead" style="background-image:url(http://33.media.tumblr.com/3695b21806de040ede270bfc8bfdd496/tumblr_mufr3eEwKX1st5lhmo1_1280.jpg)">
	<div class="wrap page-lead-content">
		<h1>Hi, I'm Kevin!</h1>
		<h3 style="font-style:italic;">I like to build things.</h3>
	</div>
</div>
<!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div>
<!-- /.tiles -->