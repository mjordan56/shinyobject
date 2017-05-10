---
layout: home
---

# Welcome To My Blog

It seems like everybody has a desire, or maybe it's a need, to be heard these days. Everyone is looking to claim their 15 minutes of fame on You Tube, Facebook, Twitter, Instagram, _{fill in the name of your favorite social media outlet here}_. Well, I guess this blog is my voice adding to the literally millions of other voices calling out into the infinite void of the internet.

My blog is a repository for me to comment on technology, applications and other geeky things that I find cool and interesting (i.e. shiny objects). I'm also going to cross-reference GitHub projects that I've created to investigate various technologies. My current interests are in the areas of Android Things, the Swift programming language and iOS app development.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.summary }} -&nbsp;{{ post.date | date: '%B %-d, %Y'}}
    </li>
    <br>
  {% endfor %}
</ul>
