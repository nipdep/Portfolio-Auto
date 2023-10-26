---
layout: landing
title: Experience
description: 'From Intern to Expert: My Professional Evolution'
image: assets/images/experience_pic1.jpg
nav-menu: true
order: 4
---

<!-- Main -->
<div id="main">

<!-- Two -->
<section id="two" class="spotlights">
	{% for post in site.posts %}
		{% if post.type == 'experience' %}
			<section class="post">
                <header class="note-header">
                    <h2 class="post-title">
                        <a href="{{ post.url | relative_url }}">
                            {{ post.title | escape }}
                        </a>
                    </h2>
                    <p class="post-meta">
                        Tagged:
                        <span>
                            {% for tag in post.tags %}
                                <a href="{{site.baseurl}}/tags/#{{ tag }}">#{{ tag }}</a>
                            {% endfor %}
                        </span>
                    </p>
                </header>
                <div class="post-description">
                    <p>
                        <em>{{ post.description | strip_html | escape | truncate: 300}}</em>
                    </p>
                </div>
            </section>
		{% endif %}
	{% endfor %}
</section>

</div>