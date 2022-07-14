---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar and site.author.semanticscholar %}
  You can find full list of publications on <a href="{{site.author.googlescholar}}">Google Scholar profile</a> or <a href="{{site.author.semanticscholar}}">Semantic Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}

<font size='3'>* co-first author</font>
