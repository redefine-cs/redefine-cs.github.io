---
layout: page
title: Program Staff
nav_order: 3
description: A listing of all the program staff members.
---

# Program Staff

This page will be updated with 2024 staff in late spring. Please reach out to `redefinecs.staff@gmail.com` if you have any general questions.

## 2023 Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
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
