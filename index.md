---
layout: default
---
<ul>
  {% for post in site.posts %}
    <li class="pre">
      <a href="/software-craftsmanship-north-site{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
