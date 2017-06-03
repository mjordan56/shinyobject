---
layout: home
---

# Welcome To My Blog

Everyone seems to be looking to claim their 15 minutes of fame on YouTube, Facebook, Twitter, Instagram, or _{fill in the name of your favorite social media outlet here}_. While many people want their voices to be heard or make a mark of their own these days this blog isn't my attempt at satisfying such a desire. I'm pretty low-key on the social media landscape. The purpose of this blog is to provide me with a respository for capturing and possibly sharing my comments on technology, applications and other geeky things that I find cool and interesting (i.e. shiny objects).

The primary reason I started this blog was to be able to share information with colleagues, friends and occasionally recruiters things that I'm doing. I hope to be able to use this blog as a tool to demonstrate working that I'm doing with Swift, iOS, Android Things or other shiny things that have attracted my attention.

When appropriate, the blog entries posted here will cross-reference associated GitHub projects that I've created to investigate various technologies. I'm creating these projects to showcase my work. If anyone else can find value in these projects please feel free to fork the project. Enjoy.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.synopsis }} -&nbsp;{{ post.date | date: '%B %-d, %Y'}}
    </li>
    <br>
  {% endfor %}
</ul>
