---
title: Future Events
permalink: /fevents/
---

{% for fevents in site.fevents %}
  <h2>

    <a href="{{ fevents.url }}">
      {{ fevents.name }} - {{ fevents.position }}
    </a>
  </h2>

<p>{{ fevents.content | markdownify }}</p>
<hr>
{% endfor %}
