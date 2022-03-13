---
layout: page
title: 2021 Staff
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

## Teaching Assistants

{% assign assistant = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in assistant %}
{{ staffer }}
{% endfor %}

## Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}

## Operations
{% assign ops = site.staffers | where: 'role', 'Operations' %}
{% for staffer in ops %}
{{ staffer }}
{% endfor %}
