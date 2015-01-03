---
layout: page
title: Archives
permalink: /Archives/
---

<ul>
	{% for posts in site.posts %}
		<li>
			<a href="{{posts.url}}">{{posts.title}}</a>
		</li>
	{% endfor %}
</ul>
