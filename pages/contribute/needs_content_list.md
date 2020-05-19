---
title: Pages that Need Content
tags: [getting_started]
sidebar: home_sidebar
permalink: /contribute/pages_that_need_content
summary: Pages that Need Content
---

## Pages that Need Content

<p>
  {% for page in site.pages %}
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

## How Edit This List
This list is automatically generated from all pages that contain the TAG "need_content" (without quotes) in the front matter. If you add content to one of these pages and it is functionally complete, please remove the "need_content" tag from that page as you finalize and publish it.
