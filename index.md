---
layout: default
---
<ul class="post-excerpts">
  {% for post in site.posts %}
    <li class="post-card">
      <div class="post-card__title">
        <a href="/software-craftsmanship-north-site{{ post.url }}">{{ post.title }}</a>
      </div>
      {{ post.excerpt }}
      <a href="/software-craftsmanship-north-site{{ post.url }}">Read more...</a>
    </li>
  {% endfor %}
</ul>
