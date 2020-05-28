---
layout: home
title: Home
nav_order: 0
description: >-
    redefine is a virtual summer program introducing high schoolers to computer science.
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

## Program Details  

**redefine** is a free, virtual summer program targeted at rising freshmen and sophomores. We seek to introduce computer science (programming and theory) to students who otherwise might not have considered it as a career option. We’re motivated by a vision of a more equitable and ethical tech industry through increased diversity and representation.

For more information about [the program](about) and [the course staff](staff) please check out the links on the left.
![](assets/illustrations/guy.png)