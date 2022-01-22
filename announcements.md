---
layout: other
title: Announcements
---

# FUTURE EVENTS WILL BE POSTED HERE


<ul>
  {% for post in site.posts %}
    <li>
        <h2><a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">{{ post.title }}</a></h2>
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date_to_string }}</time> |   {% for tag in post.tags %}<a>[{{tag}}]</a> {% endfor %}
        <p>{{ post.content | strip_html | truncatewords:50 }}</p>
    </li>
  {% endfor %}
</ul>