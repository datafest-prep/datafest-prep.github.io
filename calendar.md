---
layout: page
title: Activities and Resources
description: Listing of course modules and topics.
---

# Calendar

*Note: future dates on this schedule are approximate and subject to change.*

{% for module in site.modules %}
{{ module }}
{% endfor %}
