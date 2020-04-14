---
layout: archive
title: "Peer Reviewed Publications"
permalink: /peer-reviewed/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---

{% for post in site.peerreviewed reversed %}
  {% include archive-single.html %}
{% endfor %}
