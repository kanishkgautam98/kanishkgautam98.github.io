---
layout: archive
title: "Work Experience"
permalink: /workex/
author_profile: true
---

{% include base_path %}

{% for post in site.workex reversed %}
  {% include archive-single.html %}
{% endfor %}
