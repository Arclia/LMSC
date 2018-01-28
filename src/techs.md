---
title: Techs
layout: page
sidebar_link: true
---

{% for tech in site.techs %}
* [{{tech.title}}]({{tech.url}})
{% endfor %}