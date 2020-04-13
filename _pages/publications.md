---
layout: archive
title: ""
permalink: /publications/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---

# Peer-reviewed Papers
{% for post in site.peerreviewed reversed %}
  {% include archive-single.html %}
{% endfor %}
