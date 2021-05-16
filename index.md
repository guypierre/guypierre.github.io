---
layout: default
---

# Bienvenue chez Guypierre

Ce site présente le travail de Guypierre, sculpteur et poète.

* [Ambilogues](/ambilogues)
* [Poèmes](/poemes)
* [Sculptures](/sculptures)

# Actualités

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
