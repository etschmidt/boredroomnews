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
			<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
		{% endfor %}
		</div>

	</div>
</section>