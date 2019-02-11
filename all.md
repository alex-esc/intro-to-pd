---
layout: default
title: Welcome
---




## All posts

All my blog posts are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][l].


[l]: https://creativecommons.org/licenses/by-sa/4.0/

{% for post in site.posts %}

<article class='post'>
  <h1 class='post-title'>
    <a href="{{ site.path }}{{ post.url }}">
      {{ post.title }}
    </a>
  </h1>
  <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
  {{ post.content }}
</article>

{% endfor %}