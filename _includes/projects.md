<h2 id="projects" style="margin: 2px 0px -15px;">Projects</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.projects.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
      <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100; height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title"><a href="{{ link.page }}">{{ link.title }}</a></div>
    <div class="author">{{ link.description }}</div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
