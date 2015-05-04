---
layout: page
title: Python
permalink: /category/python/
---

{% for post in site.posts %}
<h4><a href="{{ post.url | prepend: site.baseurl  }}" class="post-title">{{ post.title }}</a></h4>
{{ post.excerpt }}
<ul class="actions">
	<li><a href="{{ post.url | prepend: site.baseurl  }}" class="button icon fa-file">Continue Reading</a></li>
</ul>
{% endfor %}
