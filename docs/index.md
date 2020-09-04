---
layout: default
---

---
# Hi, I'm Cal! 
we are pals ![logo](https://media1.tenor.com/images/967231005ac85f2acd216fb61b328ccd/tenor.gif?itemid=16050846) 

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>