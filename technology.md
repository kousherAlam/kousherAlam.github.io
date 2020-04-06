---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Technology
layout: home
---
# Technology Page
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
        <p class="lead">{{ post.title }}</p>
        <p>{{ post.topics }}</p>
      </a>
    </li>
  {% endfor %}
</ul>