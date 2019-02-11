---
layout: default
title: Welcome
---




## All lessons


This work is a derivative from "Introduction To Computer Music" by Miller Puckette, used under CC BY NC SA 3.0 unported. "Introduction To Computer Music - Explained" is licensed under [CC BY NC SA 4.0][l] by Alex Esc.


[l]: https://creativecommons.org/licenses/by-nc-sa/4.0/
 

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