---
layout: default
---
<ul class="post-excerpts">
  {% for post in site.posts %}
    <li class="post-card">
      <a href="/software-craftsmanship-north-site{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      <a href="/software-craftsmanship-north-site{{ post.url }}">Read more...</a>
    </li>
  {% endfor %}
</ul>
