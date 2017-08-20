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
  <p> </p>



  {% endfor %}
{% endfor %}
