---
layout: home
title: Portfolio
navigation_weight: 2
permalink: /portfolio/

---

<div class = "article-container">
<div class="flex-grid-thirds">
{%for post in site.categories.portfolio%}
	
		<div class="col">
			<a href = "{{post.url}}">{{post.title}}</a>
		</div>
	
{%endfor%}
</div>
</div>
