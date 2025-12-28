---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Publications

{% for post in site.publications reversed %}
  {% if post.category == 'preprint' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

