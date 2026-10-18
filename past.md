---
layout: page
title: Past Conferences
permalink: /past/
---


<ul class="post-list">
{% for edition in site.data.past %}
    <li>
        <h2><a class="poem-title" target="_blank" href="{{ edition.website }}">{{ edition.name }}, {{ edition.location }}</a></h2>
        <p class="poem-meta">{{ edition.when }}</p>
        <p class="poem-meta"><b>General Chair{% if edition.gc.size > 1 %}s{% endif %}:</b> {{ edition.gc | join: ", " }}<br>
        <b>Program Chair{% if edition.pc.size > 1 %}s{% endif %}:</b> {{ edition.pc | join: ", " }}</p>
      </li>
{% endfor %}
</ul>