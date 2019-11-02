---
layout: archive 
author_profile: true
permalink: /posts/
---

{% for post in site.posts %}
  <h2>
    <a href="{{ post.url }}">
        {{ post.title }}
    </a>
  </h2>
  <p>{{ post.content | markdownify }}</p>
{% endfor %}