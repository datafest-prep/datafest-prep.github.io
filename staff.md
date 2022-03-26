---
layout: page
title: Site Creators 
description: A listing of all the course staff members.
---

# Site Creators

The resources on this site were created by Dr. Nicole Dalzell (Assistant Teaching Professor) and Dr. Ciaran Evans (Assistant Professor) of Wake Forest University. We  both had experience with DataFest in grad school, and we hope you find these resources useful as you prepare for your own competition! If you have any comments of suggestions, please let us know! 

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
