---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
mermaid: true
---

# Welcome
Welcome to my blog, where i explore Threat Detection, Deception, and cutting-edge Cybersecurity strategies. Stay ahead of emerging threats, discover innovative defense tactics, and enhance your security mindset. 

The blog is still in development, but stay tuned for insightful content 

# Posts 
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} -  {{ post.title }}  </a>
    </li>
  {% endfor %}
</ul>



