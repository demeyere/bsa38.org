---
title: ls
date: 2018-01-13
revised: 2018-05-15 13:39 
permalink: /ls
layout: post
---

## Posts: {{ site.posts | size }}

{% assign sorted_posts = (site.posts | sort: 'title') %}
{% for post in sorted_posts %}<a href="{{ post.url }}">{{ post.title }}</a><br/>
{% endfor %}

## Pages

<a href="/about">About us</a><br/>
<a href="/calendar">Calendar</a><br/>
<a href="/calendar-archive">Calendar archive</a><br/>
<a href="/eagles">Our Eagles</a><br/>
<a href="/man">the Manual (for the website)</a><br/>
