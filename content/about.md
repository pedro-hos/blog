---
title: About
description: |
  I'm Pedro Hos a passionate software developer with over 10 years of experience working with Java. Currently, I am a Senior Software Engineer at Red Hat, working on the Application Runtime Sustaining team (Wildfly, Quarkus, Keycloak). I lead the JUG Vale community and advocate for open data and open-source initiatives. I enjoy mountain biking, writing, cooking and hiking in my free time.
layout: :theme/page
---

# About Me

I'm Pedro Hos a passionate software developer with over 10 years of experience working with Java. Currently, I am a Senior Software Engineer at Red Hat, working on the Application Runtime Sustaining team (Wildfly, Quarkus, Keycloak). I lead the JUG Vale community and advocate for open data and open-source initiatives. I enjoy mountain biking, writing, cooking and hiking in my free time.

**These are just my personal thoughts and reflections! Additionally, the views expressed here are entirely my own and do not represent the ideas or opinions of the company I work for.**

## Authors

<div class="authors">
  <!-- authors.yml is in the data/ -->
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    <!-- the author-card tag is defined in the default Roq theme -->
    {#author-card name=author.name avatar=author.avatar nickname=author.nickname profile=author.profile /}
  {/for}
</div>

