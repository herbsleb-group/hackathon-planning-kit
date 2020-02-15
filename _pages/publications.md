---
layout: splash
title: "Publications"
permalink: /publications/
author_profile: false
# sidebar:
#  nav: "main"
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
