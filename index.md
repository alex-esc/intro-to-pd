---
layout: default
title: Welcome
---


# A full University course for free

Learn to use pure data for creating basic computer music.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Pdobjects.svg/320px-Pdobjects.svg.png)

> Image credit: <a href="https://commons.wikimedia.org/wiki/User:Jancsika">Jancsika</a>, <a href="https://commons.wikimedia.org/wiki/File:Pdobjects.svg">Pdobjects</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/legalcode" rel="license">CC BY-SA 3.0</a> 

Introduction to computer music - explained is divided into bite sized lessons, we include all necessary materials to self taught Pure Data or to teach this topic to newcomers; meaning we include presentations, manuals and other resources.

**More lessons are coming soon**



## Latest Lesson



{% for post in site.posts limit:1 %}


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


## Older lessons

Find older lessons on the _[lessons menu](archive.md)_, or get notified when a new lesson comes out of via _[RSS](feed.xml)_.



This work is a derivative from "Introduction To Computer Music" by Miller Puckette, used under CC BY NC SA 3.0 unported. "Introduction To Computer Music - Explained" is licensed under [CC BY NC SA 4.0][l] by Alex Esc.


[l]: https://creativecommons.org/licenses/by-nc-sa/4.0/
 