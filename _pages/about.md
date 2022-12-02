---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Software Engineer with a master's degree in Deep Learning. I'm currently working as a Software Engineer at NotCo.

I have experience developing with Node (express, koa, React, React Native, Vue), Python (Django, Flask, PyTorch), Ruby (Ruby on Rails) and C.

I enjoy playing video games, board games and music.

---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
