---
layout: page
title: Program Staff
nav_order: 2
description: A listing of all the program staff members.
---

# Program Staff

Please reach out to `redefinecs.staff@gmail.com` if you have any general questions.

## Instructors & Mentors

{% assign instructors = site.staffers %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

