---
layout: page
title: Program Staff
nav_order: 2
description: A listing of all the program staff members.
---

# Program Staff

Please reach out to `staff@redefine-cs.org` if you have any general questions.

## 2024 Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' | where: 'active', true | sort: 'order' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Former Teaching Assistants

{% assign assistant = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in assistant %}
{{ staffer }}
{% endfor %}

## Former Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
