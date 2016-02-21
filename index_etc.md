---
layout: default
title: About IT 노트
---

<!-- Posts -->
<ul id="posts">
     <p>1234{{ page.category }}</p>

     {% for post in paginator.posts %}
          <p>{{post.category == "env"}}</p>
	  <li class="post">
	  	<h3><a href="{% if site.baseurl == "/" %}{{ post.url }}{% else %}{{ post.url | prepend: site.baseurl }}{% endif %}">{{ post.title }}</a></h3>
	  	<time datetime="{{ post.date | date_to_xmlschema }}" class="by-line">{{ post.date | date_to_string }}</time>
	  	<p>{{ post.content | strip_html | truncatewords:30 }}</p>
	  </li>

    {% endfor %}

</ul>
