---
title: Pages that Need Content
tags: [getting_started]
sidebar: home_sidebar
permalink: /contribute/pages_that_need_content
summary: Pages that Need Content
---

## Pages that Need Content

<p>
  {% for page in site.pages | group_by: "categories" %}
  	<ul>
  	{% for tag in page.tags %}
  		{% if tag == "need_content" %}
    	<li><a href="{{page.url | relative_url}}">{{ page.title }}</a> - {{ page.permalink }}</li>
    	{% endif %}
    {% endfor %}
	</ul>
  {% endfor %}
</p>

<br>