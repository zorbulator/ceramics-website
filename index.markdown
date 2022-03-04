---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "My ceramics work"
permalink: /
---

# Posts

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>

# About Me

I'm taking ceramics as my required art class, but I actually really like it. I like being able to make stuff that's actually useful and work in three dimensions. I think my favorite project was making a platter with sgraffito because I always like trying new techniques and carving a pattern into a piece of clay is cool. I made this website using the default Jekyll built in to GitHub Pages because I don't want to use Google Sites but I'm also too lazy to set up my own server or static site generator.
