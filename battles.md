---
layout: page
title: EB Reference Guide
subtitle: KawG-E
description: This is a list of Kingdoms at War Epic Battles and full of usefule tips and instructions on how to beat them.
---
## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page lists all of the epic battles information such as how to beat them and what drops come from each one!
</p>

<div class="related">
----------------------------------------------------------------------------------------
 <div class="posts">
     duh
  {% for eb in paginator.ebs %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ eb.url | remove_first: '/'}}">
        {{ eb.title }}
      </a>
    </h1>

    <span class="post-date">{{ eb.date | date_to_string }}</span>

    {{ eb.description }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
----------------------------------------------------------------------------------------
<h5>Cats</h5>
 {% for category in site.eb.categories %}
    {% assign cat = category[0] %}
    <h6><a href="#">{{ cat }}</a></h6>
    {% for eb in site.categories[cat] %}
        <a href="{{ eb.url }}">{{ eb.title }}</a> <small>{{ eb.date }}</small>
    {% endfor %}
{% endfor %}
----------------------------------------------------------------------------------------
    


</div>

##### KAW Guide - Kingdoms At War Epic Battles Walkthroughs


