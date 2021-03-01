---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar and site.author.semanticscholar %}
  You can also find my articles on <a href="{{site.author.googlescholar}}">Google Scholar profile</a> or <a href="{{site.author.semanticscholar}}">Semantic Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-pub.html %}
{% endfor %}
