---
layout: page
title: Tech
comments: false
---

<!-- Begin List Posts
================================================== -->
<section class="recent-posts">
	<div class="section-title">
	    <h2>Archive of posts in <span>Technology</span></h2>
	</div>
	<div class="row listrecent">

	{% for post in site.categories.Tech %}

	    {% include postbox.html %}

	{% endfor %}

	</div>
</section>