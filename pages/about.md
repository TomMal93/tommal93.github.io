---
layout: page
title: O mnie
permalink: /about/
weight: 2
---

# **Kilka słów o mnie**

Cześć i chwała rodzajowi ludzkiemu. <br>
Jestem **{{ site.author.name }}** :wave:. Jestem człowiekiem, który posiada ręce i nogi. <br>
Uwielbiam oddychać, spożywać pokarm i inne takie. Przybyłem tutaj w celu replikacji mojego DiEnEj. <br>


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>