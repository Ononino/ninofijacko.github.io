---
layout: single
title: Projects
permalink: /projects/
author_profile: true
---

<style>

.project p {
  font-size: 20px;
}

</style>

{% for project in site.projects %}
<div class="project">
 <h2> <a href="{{project.url}}"> {{ project.title }} </a> </h2>
 <img src="/assets/images/{{project.imgname}}" alt="Mountain">
  <p>{{ project.description }}</p>
</div>
{% endfor %}
