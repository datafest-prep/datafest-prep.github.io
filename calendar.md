---
layout: page
title: Activities and Resources
description: Listing of course modules and topics.
---

# Activities

*Note: The activities are designed to be completed in order, but feel free to skip around if you have some experience with R!*

{% for module in site.modules %}
{{ module }}
{% endfor %}
