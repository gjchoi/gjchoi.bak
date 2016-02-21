---
layout: default
title: About IT 노트
---

### 기타 자료실

<!-- Posts -->
<ul id="posts">

	{% for post in paginator.posts %}
    {% if post.category == "env" %}
	  <li class="post">
	  	<h3><a href="{% if site.baseurl == "/" %}{{ post.url }}{% else %}{{ post.url | prepend: site.baseurl }}{% endif %}">{{ post.title }}</a></h3>
	  	<time datetime="{{ post.date | date_to_xmlschema }}" class="by-line">{{ post.date | date_to_string }}</time>
	  	<p>{{ post.content | strip_html | truncatewords:30 }}</p>
	  </li>
	  {% endif %}

    {% endfor %}

</ul>
