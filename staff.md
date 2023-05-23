---
layout: page
title: Program Staff
nav_order: 3
description: A listing of all the program staff members.
---

# Program Staff

More details on 2023 staff coming soon. Please reach out to `redefinecs.staff@gmail.com` if you have any general questions.

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## 2021 Teaching Assistants

{% assign assistant = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in assistant %}
{{ staffer }}
{% endfor %}

## 2021 Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
