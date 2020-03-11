---
layout: archive
title: "Guides"
permalink: /guides/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---
<style>
    p {
        text-align: justify;
    }
</style>
<p>We've put together a number of resources which we think is useful for hackathon organizers. Please let us know if you think we've missed out some useful resources, we will add them to our list.</p>

{% for post in site.guides %}
  {% include archive-single0.html %}
{% endfor %}
