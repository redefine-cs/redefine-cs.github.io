---
layout: home
title: Home
nav_order: 0
description: >-
    Just the Class is a modern, highly customizable, responsive Jekyll theme
    for developing course websites.
---

{: .mb-2 }
{% if site.logo %}
  <div class="site-logo"></div>
{% else %}
  {{ site.title }}
{% endif %}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
{% endif %}

## redefine 

**redefine** is a virtual summer program targeted at rising freshmen and sophomores to computer science. We seek to introduce CS (programming and theory) to students who otherwise might not have considered it as a career option. We’re motivated by a vision of a more equitable and ethical tech industry through increased diversity and representation.

For more information about [the program](about), [the curriculum](curriculum), and the [course staff](staff) please check out the links on the left.