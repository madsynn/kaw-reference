---
layout: page
title: EB Reference Guide
description: This is a list of Kingdoms at War Epic Battles  full of usefule tips and instructions on how to beat them.
tags: KAWG, KAW, kingdoms at war, ebs, epic battles
---

## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>
<div class="related">
    <h2>Epic Battles</h2>
    <ul class="related-posts">
        {% for ebs in site.eb limit:10 %}
        <li>
            <h3>
                <a href="{{ eb.url }}">
                {{ eb.title }}


                </a>
            </h3> <small>{{ eb.date | date_to_string }}</small>
        </li>
        {% endfor %}
    </ul>
</div>
