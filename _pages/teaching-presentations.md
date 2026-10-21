---
layout: single
title: "Teaching & Presentations"
permalink: /teaching-presentations/
author_profile: true
description: "Teaching, mentorship, and selected scientific presentations by Thanh-Tai Duong, Ph.D."
---

## Teaching and mentorship

Teaching and academic collaboration have included biomedical imaging technology, image processing, biomedical information systems, physics laboratory, biophysics, and capstone projects. I have supervised and mentored more than 25 undergraduate thesis and research projects.

{% for post in site.teaching reversed %}
### {{ post.title }}

{{ post.content }}
{% endfor %}

## Selected presentations

{% for post in site.talks reversed %}
### {{ post.title }}

**{{ post.type }}** · *{{ post.venue }}* · {{ post.date | date: "%Y" }} · {{ post.location }}

{{ post.content }}
{% endfor %}

See the [full publication list](/publications/) or [download the current CV](/files/01_Duong_CV.pdf).
