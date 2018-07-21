---
layout: home
title: Projects
navigation_weight: 1
permalink: /projects/

---

<div class = "article-container">
<div class="flex-grid-thirds">
{%for post in site.categories.projects%}
	
	<div class = "col"> 
		<a href = "{{post.url}}"> <div class="col-inner">{{post.title}}</div></a>
	</div>

	
{%endfor%}
</div>
</div>


