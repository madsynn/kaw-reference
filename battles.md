---
layout: page
title: EB Reference Guide
description: This is a list of Kingdoms at War Epic Battles  full of usefule tips and instructions on how to beat them.
---

## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>

<div class="related">
    <h2>Epic Battles</h2>
    <ul class="related-posts">
        {% for eb in site.ebs %}
        <li>
        <div style="float:left"><img src="http://via.placeholder.com/150x150"></div>
            <h2 style="float:left">
                <a href="{{ site.baseurl }}{{ eb.url }}">
                  {{ eb.title }}

                  </a>

            </h2>
            <br>
       <small>{{ eb.date | date_to_string }}</small>
        </li>
        {% endfor %}
    </ul>
</div>



