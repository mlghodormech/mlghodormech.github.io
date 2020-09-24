---
layout: default
---


# Hi, I'm Cal! 
we are pals 

---


<ul  class="blog">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>