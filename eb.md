---
layout: page
title: EB Reference Guide
subtitle: hello
---

## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
  Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>



{% for eb in site.ebs %}
  <h2>{{ eb.title }}</h2>
  <p>Performed by {{ eb.artist }}{% if eb.director %}, directed by {{ eb.director }}{% endif %}</p>
  {% for work in eb.works %}
    <h3>{{ eb.title }}</h3>
    <p>Composed by {{ work.composer }}</p>

  {% endfor %}
{% endfor %}
