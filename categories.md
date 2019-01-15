---
layout: page
title: Topics
comments: false
---

<!-- Begin List Posts
================================================== -->
<section class="recent-posts">
	<div class="section-title">
		<div id="archives">
		{% for category in site.categories %}
			<div class="archive-group">
		    {% capture category_name %}{{ category | first }}{% endcapture %}
		    	<div id="#{{ category_name | slugize }}"></div>
		    	
		    	<h3 class="category-head"><a href="{{ site.baseurl }}{{site.categories[category_name] }}>{{ category_name }}</a></h3>
		    
		    	<a name="{{ category_name | slugize }}"></a>
		    	{% for post in site.categories[category_name] %}
		    	<article class="archive-item">
		      		<h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
		    	</article>
		    	{% endfor %}
		    </div>
		{% endfor %}
		</div>

	</div>
</section>