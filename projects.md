---
layout: page
title: Projects
permalink: /projects/
---

Tell us about your blog. Hopefully it's cool.

[test](https://raw.githubusercontent.com/anirudhkm/anirudhkm.github.io/master/_projects/2017-01-05-opiate-prescription-analysis-using-machine-learning.markdown)

<ul class="listing">
{% for post in site.projects %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
