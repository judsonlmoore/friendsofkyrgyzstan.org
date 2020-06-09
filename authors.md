---
title: 			Authors
subtitle:		The voice of the people on our blog
description:	These are the people who have contributed to this website's content.
---


**Thank you to our wonderful authors!** Over the years many PCVs, RPCVs, counterparts, colleagues, and staff have all contributed to the content found on the [blog]({{ site.url }}/blog/). If you would also like to be a contributing offer, please [contact us]({{ site.url }}/contact/) with a pitch for what you might like to write about. 

Topic suggestions for blog posts: 
- Why you wanted to become a Peace Corps Volunteer
- What was it like arriving to Kyrgyzstan? 
- What was it like ending your service? 
- What did you accomplish as a PCV?
- What is the legacy you left behind with your work? 
- What advice would you give to others about Peace Corps or Kyrgyzstan?

We are eager to hear your story soon!

## Authors

<div class="row row-cols-1 row-cols-md-2">
{% for author in site.authors %}
  <div class="col-sm-6">
    <div class="card mb-3">
      <div class="card-body">
        <h5 class="card-title">{{ author.name }}, {{ author.position }}</h5>
        <p class="card-text">{{ author.content | markdownify }}</p>
        <a href="{{ site.url }}/authors/{{ author.short_name }}" class="btn btn-primary">View posts</a>
      </div>
    </div>
  </div>
{% endfor %}
</div>