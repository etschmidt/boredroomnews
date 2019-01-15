---
layout: page
title: Tech
comments: false
---

<!-- Begin List Posts
================================================== -->
<section class="recent-posts">
	<div class="section-title">
		<div id="archives">
		{% for post in site.categories.Tech %}
	    	<article class="row listrecent">
	      		{% include postbox.html %}
	    	</article>
		{% endfor %}
		</div>

	</div>
</section>