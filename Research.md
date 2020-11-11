---
layout: default
title: About
permalink: /research/
---

![](images/Family4.jpg")

# Hua Lin, Ph.D

  
[**Home**](/)  \  [**About me**](/about.md) \  [**Publications**](/publications.md) \ [**Research**](/research) \ [**Workshops**](/workshop.md) 

***********

<img style="float: left; width: 270px; margin: 10px 20px 20px" src="images/Me_regards1.png">

## Research

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
