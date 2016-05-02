---
layout: article
title: "Hangar"
date: 2014-06-02T09:44:20-04:00
modified: 2014-08-27T14:56:44-04:00
excerpt: "Major Kong's Aircraft"
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---


<div class="tiles">
{% for post in site.categories.hangar %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->