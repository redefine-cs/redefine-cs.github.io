---
layout: page
title: Staff
nav_order: 4
description: A listing of all the course staff members.
---

# Program Staff

Please reach out to `redefinecs.staff@gmail.com` if you have any general questions. 

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
