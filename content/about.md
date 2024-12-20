---
title: About
description: |
  Roq stands out in the Java development community as a powerful static site generator, bridging the gap between the
  likes of Gatsby, Hugo, and the broader backend community. With GitHub Actions support out-of-the-box, Roq is easy to use for beginners, but also flexible enough to provide
  Java hooks for advanced users.
layout: :theme/page
---

# About Me

I'm Pedro Hos a passionate software developer with over 10 years of experience working with Java. Currently, I am a Senior Software Engineer at Red Hat, working on the Application Runtime Sustaining team (Wildfly, Quarkus, Keycloak). I lead the JUG Vale community and advocate for open data and open-source initiatives. I enjoy mountain biking, writing, cooking and hiking in my free time.

## Authors

<div class="authors">
  <!-- authors.yml is in the data/ -->
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    <!-- the author-card tag is defined in the default Roq theme -->
    {#author-card name=author.name avatar=author.avatar nickname=author.nickname profile=author.profile /}
  {/for}
</div>

