---
title: 			Blog
subtitle:		Stories from those who served
description:	A collection of blog posts written by Kyrgyzstan RPCVs.
---


The Friends of Kyrgyzstan blog features original and cross-posted content from current and returned Peace Corps Volunteers serving in Kyrgyzstan, Peace Corps staff, and others who have been part of the work performed by PCVs. If you would like contribute content to this blog, please read the posting guidelines on the [author's page]({{ site.url }}/authors/). 

<div class="row row-cols-1 row-cols-sm-2 row-cols-md-3">
	{% for post in site.posts %}
	{% include postbox.html %}
	{% endfor %}
</div>