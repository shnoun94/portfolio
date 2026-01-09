---
layout: page
title: About
permalink: /about/
weight: 3
image: ../img/avatar.jpg
---

# **About Me**

Salut je suis **{{ site.author.name }}** :wave:,<br>
Je suis étudiante en première année de dév web chez Epitech.<br>
Passionée par le numérique et les création, j'apprends à concevoir des sites en alliant technique, logique et créativité.<br> Curieuse et motivé, je développe mes compétences jour après jour à travers des projets concrets, avec l'envie de progresser.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>