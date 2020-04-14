---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---

## Peer-reviewed papers
{% for post in site.peerreviewed reversed %}
  {% include archive-single.html %}
{% endfor %}

## Workshop papers and Technical reports
{% for post in site.workshops reversed %}
  {% include archive-single.html %}
{% endfor %}

## Workshop proceedings
{% for post in site.workshopprocs reversed %}
  {% include archive-single.html %}
{% endfor %}
