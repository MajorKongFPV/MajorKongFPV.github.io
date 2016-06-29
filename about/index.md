---
layout: article
title: "About MajorKong.com"
date: 
modified: 
excerpt: "About MajorKong.com"
image:
  feature: MajorKongLogo1600.png
  teaser: 
  thumb:
share: false
ads: true
---

This is a work in progress.

MajorKong.com is named for the atomic-bomb riding cowboy in [Dr. Strangelove](http://www.imdb.com/title/tt0057012/) who seemed to enjoy his plummet to earth.

We're using this site to post videos, track my progress, and gather information we have found helpful about learning to fly FPV.  Maybe someday it will even be a conduit for companies to send us gear to crash test!

<div class="tiles">
	{% for author in site.data.authors %}
		 <div class="author_tile">
			<img src="{{ site.url }}/images/{{ author[1].avatar }}" alt="{{ author.name }}">
	  		<h2 class="post-title">{{ author[1].name }}</h2>
	  		<p class="post-excerpt">{{ author[1].bio }}</p>
			<b>Stats</b>
			<br>
			Frames broken: {{ author[1].stats.frames }}<br>
			Quads lost: {{ author[1].stats.lost }}<br>
			Lost quads recovered: {{ author[1].stats.recovered }}<br>
			ESCs fried: {{ author[1].stats.escs }}<br>
		</div>
	{% endfor %}
</div>
