---
layout: default
---

<div class="posts">
  {% for version in site.versions %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ version.url }}">{{ version.title }}</a></h1>

      <div class="entry">
        {{ version.excerpt }}
      </div>

    </article>
  {% endfor %}
</div>
