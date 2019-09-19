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
    
{% for eb in site.ebs %}
  <h2>
    <a href="{{ site.baseurl }}{{ eb.url }}">
      {{ eb.title }}  
    </a>
  </h2>
 
{% endfor %}


 <div class="posts">
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

<!-- Pagination links -->
<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}" class="previous">
      Previous
    </a>
  {% else %}
    <span class="previous">Previous</span>
  {% endif %}
  <span class="page_number ">
    Page: {{ paginator.page }} of {{ paginator.total_pages }}
  </span>
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}" class="next">Next</a>
  {% else %}
    <span class="next ">Next</span>
  {% endif %}
</div>
----------------------------------------------------------------------------------------
 
----------------------------------------------------------------------------------------
        <h1>Epic Battles</h1>
    <ul class="related-posts">
        {% for eb in site.ebs  | sort: category %}
        <li style="clear:both">
            {% if eb.photo_path %}
                <img src="{{ eb.photo_path }}" alt="{{ eb.name }}" style="float:left; width:75px; margin:15px;" itemprop="image">
            {% endif %}  
            
            <h2 style="float:left">
                  <a href="{{ site.baseurl }}{{ eb.url }}" itemprop="url" style="">
                    <span itemprop="name">{{ eb.title }}</span>                     
                  </a>   
            </h2>
            <br>
            <p  itemprop="description" style="float:left">
                   <span style="font-size:1em;"> {{ eb.description | truncate: 120 }}</span>
            </p>
            <small style="font-size:.75em; float:right;">{{ eb.category }}</small>
            
            <br style="clear:both" />

       <hr />
        </li>
        {% endfor %}
    </ul>


</div>

##### KAW Guide - Kingdoms At War Epic Battles Walkthroughs


