---
layout: post
title: Competitions
description:
permalink: /competitions/
nav-menu: true
---

Competitions are a great way to meet other cubers and to have a good time. For most people, it's not about the competitive aspect, but rather about getting to participate in the local cubing community. The club hosted its first official competition in 2017, and has since aimed to organize one every semester. Our competitions are sanctioned by the World Cube Association (meaning results are internationally accepted).

{% if site.comp_date %}
Our next competition is scheduled to take place {{ site.comp_date }}.
{% if site.comp_url %}
If you're interested in competing, please visit the competition website [here]({{ comp_url }}) for more information, and to register. Registration is free for WPI students and faculty, but it is first come first serve, so please sign up as soon as possible if you would like a spot.
{% else %}
We'll have more information about this very soon, which will be announced both by email and on this page.
{% endif %}
{% else %}
We don't have a date for our next competition yet, but when we do, it will be announced by email and on this page.
{% endif %}
