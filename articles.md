---
layout: article
title: Articles
---
<ul>
  {% for article in site.articles %}
    <li>
      <h2><a href="{{ article.url }}">{{ article.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
