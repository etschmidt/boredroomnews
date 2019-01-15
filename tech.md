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
	    	<article class="archive-item">
	      		<h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
	    	</article>
		{% endfor %}
		</div>

	</div>
</section>