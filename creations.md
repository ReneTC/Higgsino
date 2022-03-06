---
layout: default
title: Videos
---
<h1>List of all videos</h1>
<a href="{{ site.github.repository_url }}/tree/master/{{ page.relative_path }}">Edit</a>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
