---
layout: page
title: Technology
comments: false
---

<!-- Posts Index
================================================== -->
<section class="recent-posts" id="tech-archive">
    
    <div class="row listrecent">

        {% for post in site.categories.tech %}

               {% include postbox.html %}          

        {% endfor %}
        
    </div>
    
</section>

<!-- Pagination
================================================== -->
<div class="bottompagination">
	<div class="pointerup"><i class="fa fa-caret-up"></i></div>
	<span class="navigation" role="navigation">
	    {% include pagination.html %}
	</span>
</div>