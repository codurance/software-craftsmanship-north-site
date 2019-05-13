---
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="/software-craftsmanship-north-site{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
