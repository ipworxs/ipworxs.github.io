---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
mermaid: true
permalink: /blog/
---

Under Construction

# Posts 
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} -  {{ post.title }}  </a>
    </li>
  {% endfor %}
</ul>

