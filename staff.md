---
layout: page
title: Program Staff
nav_order: 2
description: A listing of all the program staff members.
---

# Program Staff

Please reach out to `redefinecs.staff@gmail.com` if you have any general questions.

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}

