---
layout: home
---

# Welcome To My Blog

Everyone seems to be looking to claim their 15 minutes of fame on You Tube, Facebook, Twitter, Instagram, _{fill in the name of your favorite social media outlet here}_. While it seems like everybody has a desire to be heard these days this isn't my attempt at satisfying such a desire. I'm pretty low-key on the social media landscape. The purpose of this blog is to provide me with a respository for capturing and sharing my comments on technology, applications and other geeky things that I find cool and interesting (i.e. shiny objects).

The primary reason I started this blog was to be able to share with colleagues, friends and recruiter things that I'm doing. I hope to be able to use this blog as a tool to demonstrate working that I'm doing with Swift, iOS, Android Things or other shiny things that have attracted my attention.

I'm going to cross-reference by blog post with associated GitHub projects that I've created to investigate various technologies. I'm creating these projects to showcase my work. If anyone else can value in these projects please feel free to fork the project.

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
