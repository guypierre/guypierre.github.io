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

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Voir plus</a>
    </article>
  {% endfor %}
</div>
