---
layout: page
title: Announcements
nav_exclude: true
description: A feed containing all of the class announcements.
---

# Announcements
Test data 

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
