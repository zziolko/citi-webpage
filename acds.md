---
layout: page 
title: Advanced Computing and Data Science 
permalink: /acds/
---

{% for i in site.data.acds %}

<div class="row">
<div class="three columns" style="text-align: center;" id="name">
  <img src="{{ i.picture }}" class="avatar u-max-full-width">
</div>

<div class="six columns">
{{ i.name }}
  <a href="mailto:{{ i.mail }}">{{ i.mail }}</a>
</div>
</div>

{% endfor %} 