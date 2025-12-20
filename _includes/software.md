<h2 id="open-source-software" style="margin: 2px 0px -15px;">Open Source Software</h2>
<div style="margin-top: 20px;"></div>

<div class="software">
<ul style="margin:0 0 20px;">

{% for project in site.data.software.projects %}

<li style="margin-bottom: 15px;">
  <strong>{{ project.name }}</strong>
  <br>
  {{ project.description }}
  <br>
  <div class="links" style="margin-top: 5px;">
    {% if project.github %}
    <a href="{{ project.github }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
    {% endif %}
    {% if project.website %}
    <a href="{{ project.website }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Website</a>
    {% endif %}
  </div>
</li>

{% endfor %}

</ul>
</div>
