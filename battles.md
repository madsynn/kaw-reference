---
layout: page
title: EB Reference Guide
subtitle: KawG-E
description: This is a list of Kingdoms at War Epic Battles  full of usefule tips and instructions on how to beat them.
---
## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>

<div class="related">
    <h1>Epic Battles</h1>
    <ul class="related-posts">
        {% for eb in site.ebs %}
        <li>
            <h2 style="float:left">
                <a href="{{ site.baseurl }}{{ eb.url }}" itemprop="url" style="width:75px">
                {% if eb.photo_path %}
                <img src="{{ eb.photo_path }}" alt="{{ eb.name }}" style="float:left" itemprop="image">
                {% endif %}
                  <span itemprop="name">{{ eb.title }}</span>
                  </a><br>
            </h2>
            <br>
            <p  itemprop="description">
                    {{ eb.description | truncate: 160 }}<
            </p>
            <br style="clear:both" />

       <hr />
        </li>
        {% endfor %}
    </ul>
</div>
