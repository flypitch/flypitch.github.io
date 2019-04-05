---
layout: archive
permalink: /
image:
  feature: flypitch.svg
---


<div class="tiles">
{% for post in site.posts %}
        {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<center>
<a href="https://formalabstracts.github.io">
<image src="images/fabstracts.png"/>
</a>
  &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;
    &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;
	  &#160;&#160;&#160;
<a href="https://leanprover.github.io">
<image src="images/lean_logo.svg"/>
</a>
</center>

<!-- <div class="tiles"> -->
<!-- {% for post in site.posts %} -->
<!-- 	{% include post-grid.html %} -->
<!-- {% endfor %} -->
<!-- </div><\!-- /.tiles -\-> -->
