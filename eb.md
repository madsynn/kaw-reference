---
layout: page
title: EB Reference Guide
subtitle: hello
---

## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
  Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>


-------------------------------------------------------


<div class="related">
  <h2>Epic Battles</h2>
  <ul class="related-posts">
    {% for eb in site.eb limit:10 %}
      <li>
        <h3>
          <a href="{{ eb.url }}">
            {{ eb.title }}
            <small>{{ eb.date | date_to_string }}</small>
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>

</div>
-------------------------------------------------------
