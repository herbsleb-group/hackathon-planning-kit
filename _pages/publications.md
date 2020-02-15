---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
sidebar:
  nav: "main"
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
