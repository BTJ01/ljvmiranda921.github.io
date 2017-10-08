---
layout: page
title: Notebook
description: Notes of Lester James V. Miranda
permalink: /notebook/
---

Here I write about the things that interest me: thoughts on a certain
topic, solutions for an online course, or tutorials for a specific
problem. As of now, I would like to treat this page as a repository of
the things that I experiment on, so expect that
I'll be posting a lot from a wide range of topics!

<ul>
  {% for post in site.categories.notebook %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>