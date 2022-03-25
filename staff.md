---
layout: page
title: Site Creators 
description: A listing of all the course staff members.
---

# Site Creators

The resources on this site were created by Dr. Nicole Dalzell (Asssitant Teaching Professor) and Dr. Ciaran Evans (Asssitant Professor) of Wake Forest University. We hope you find these resources useful! If you have any comments of suggestions, please let us know! 

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
