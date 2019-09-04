---
layout: page
title: EB Reference Guide
subtitle: KawG-E
description: This is a list of Kingdoms at War Epic Battles and full of usefule tips and instructions on how to beat them.
---
## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page lists all of the epic battles information like how to beat them and what drops come from each one!
</p>

<div class="related">
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
                    {{ eb.description | truncate: 120 }}<
            </p>
            <br style="clear:both" />

       <hr />
        </li>
        {% endfor %}
    </ul>

</div>

##### KAW Guide - Kingdoms At War Epic Battles Walkthroughs


