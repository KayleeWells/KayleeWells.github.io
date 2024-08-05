---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

Peer-Reviewed Publications
---
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Work in Progress
---
{% for post in site.workinprogress reversed %} 
  {% include archive-single.html %} 
{% endfor %}

Published Datasets
---
{% for post in site.datasets reversed %}
  {% include archive-single.html %}
{% endfor %}
