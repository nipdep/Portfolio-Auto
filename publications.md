---
layout: landing
title: Publications
description: 'Data Whisperer: My Quest for AI Excellence'
image: assets/images/pic03.jpg
nav-menu: true
order: 2
---

<!-- Main -->
<div id="main">
<!-- Two -->
<section id="two" class="spotlights">
	{% for post in site.posts %}
		{% if post.type == 'publication' %}
			<section>
				<div class="thumbnail">
					<a href="{{ site.baseurl }}{{ post.url }}" class="image">
						<img src="{{site.baseurl}}/{{ post.image }}" alt="" data-position="center center" />
					</a>
				</div>
				<div class="content">
					<div class="inner">
						<header class="major">
							<h3>{{ post.title }}</h3>
						</header>
						<p>{{ post.description }} {{ post.categories }}</p>
						<ul class="actions">
							<li><a href="{{ site.baseurl }}{{ post.url }}" class="button">Learn more</a></li>
						</ul>
					</div>
				</div>
			</section>
		{% endif %}
	{% endfor %}
</section>

</div>