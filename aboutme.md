---
layout: page
title: Bio
subtitle: 
---

My name is Giovanni Catalani. This is my professional website: I am a PhD Researcher at Airbus and ISAE-Supaero in Toulouse, France. Here you can find some information about me, my CV, published research and given talks.
For more information or have a chat, you can contact me directly.

## Latest updates

<ul>
{% assign ups = site.posts 
     | where_exp: "p", "p.tags contains 'update'" 
     | sort: "date" | reverse %}
{% for post in ups limit:5 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>— {{ post.date | date: "%b %-d, %Y" }}</small>
  </li>
{% endfor %}
</ul>