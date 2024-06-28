---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---

{% include base_path %}

<h2>
{% for post in site.presentations reversed %}
  {% include archive-single-presentations.html %}
{% endfor %}
</h2>

