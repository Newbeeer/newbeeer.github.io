---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---

> _Set your course by the stars, not by the lights of every passing ship._


<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>

