---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a full list on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  <div class="wordwrap">Click on titles for abstracts and graphic summaries!</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
