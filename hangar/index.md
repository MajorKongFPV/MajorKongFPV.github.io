---
layout: article
title: "Hangar"
date: 
modified:
excerpt: "Major Kong's Aircraft"
image:
  feature: MajorKongLogo1600.png
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