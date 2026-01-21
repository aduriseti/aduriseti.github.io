---
layout: default
---

# {{ site.title }}
{{ site.description }}

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>
      <br><small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>