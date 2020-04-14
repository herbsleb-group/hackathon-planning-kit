---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---

## Peer-reviewed Papers
{% for post in site.peerreviewed reversed %}
  {% include archive-single.html %}
{% endfor %}

## Peer-reviewed Papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
