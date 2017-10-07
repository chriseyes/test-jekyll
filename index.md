---
layout : default
title : page test
description : premier site en jekyll
---

{{ site.title }}

# Test

Nouvelle page de test

<ul>
{% for page in site.html_pages %}
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>