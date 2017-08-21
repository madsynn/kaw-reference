---
layout: page
title: EB Reference Guide
description: This is a list of Kingdoms at War Epic Battles  full of usefule tips and instructions on how to beat them.
tags: [ ".vimrc", "plugins", "spf13-vim", "vim" ]
lastmod: 2015-12-23
categories:
  - "Development"
  - "VIM"
slug: "spf13-vim-3-0-release-and-new-website"
---

## Kingdoms At War (KAW) EB Reference Guide

<p class="message">
    Hi there! This page is included as an example. Feel free to customize it for your own use upon downloading. Carry on!
</p>
<div class="related">
    <h2>Epic Battles</h2>
    <ul class="related-posts">
        {% for eb in paginator.ebs %}
        <li>
        <div><img src="" /></div>
            <h3>
                <a href="{{ eb.url }}">
                  {{ eb.title }}
                  </a>
            </h3> <small>{{ eb.date | date_to_string }}</small>
        </li>
        {% endfor %}
    </ul>
</div>



