---
layout: page
title: Home
---

# Hello Elves! (This is word!)

<p>
   <img src="stranky_ve _vystavbe.jpg" alt="stranky_ve _vystavbe" width="500" height="300">
  </p>

Podívejte se na příspěvky:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
