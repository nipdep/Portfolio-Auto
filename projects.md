---
layout: landing
title: "Projects"
description: 'Innovate, Create, Repeat: My Project Journey'
image: assets/images/pic01.jpg
nav-menu: true
order: 3
---

<!-- Main -->
<div id="main">

<!-- One -->
<!-- <section id="one">
	<div class="inner">
		<header class="major">
			<h2>Sed amet aliquam</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna. Maecenas massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Nullam et orci eu lorem consequat tincidunt vivamus et sagittis magna sed nunc rhoncus condimentum sem. In efficitur ligula tate urna.</p>
	</div>
</section> -->

<!-- Two -->
<section id="two" class="spotlights">
	{% for post in site.posts %}
		{% if post.type == 'projects' %}
			<section>
				<div class="thumbnail">
					<a href="{{ site.baseurl }}{{ post.url }}" class="image">
						<img src="{% link {{ post.image }} %}" alt="" data-position="center center" />
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