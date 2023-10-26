---
layout: landing
title: Who am I?
image: assets/images/pic02.jpg
nav-menu: true
order: 1
---
{% assign data = site.data.personal %}
<!-- Main -->
<div id="main" class="alt">
	<!-- Two -->
	<section id="one">
		<div class="inner no-padding">
			<header class="major">
				<h1>Me ?</h1>
			</header>
			<div>
				<p class='actions'>{{ data.description }}</p>
			</div>
			<div class="row">
				<div class="6u 12u$(small)">
					<div class="table-container">
					<table>
						{% for d in data.details %}
						<tr>
							<td class="first-column"><a href="#" class="button special small disable">{{ d.key }}</a></td>
							<td class="second-column"><a href="#" class="button small disable">{{ d.value }}</a></td>
						</tr>
						{% endfor %}
					</table>
					</div>
				</div>
				<div class="6u$ 12u$(small)">
					<!-- <h3>Technologies</h3> -->
					<div class='logos-container'>
					</div>
				</div>
			</div>
		</div>
	</section>
	<section id="one">
		<div class="inner no-padding">
			<div class="row">
				<div class="6u 12u$(small)">
					<header class="major">
						<h1>Fields of Interest</h1>
					</header>
					<p class='actions'>
						{% for d in data.fields_of_interest %}
						<a href="#" class="button small disable">{{ d }}</a>
						{% endfor %}
					</p>
				</div>
				<div class="6u$ 12u$(small)">
					<header class="major">
						<h1>Soft Skills</h1>
					</header>
					<p class='actions'>
						{% for d in data.soft_skills %}
						<a href="#" class="button small disable">{{ d }}</a>
						{% endfor %}
					</p>
				</div>
			</div>
		</div>
	</section>
	<section id='second'>
		<div class='inner no-padding'>
			<header class="major">
				<h1>Certificates</h1>
			</header>
			<ul class="fa-ul">
				{% for d in data.certificates %}
				<li>
					<i class="fa-li fa fa-check-square"></i>{{ d.title }}
					<a href="#">
						<i class="fas fa-arrow-right"></i>
						{{ d.link }}
					</a>
				</li>
				{% endfor %}
			</ul>
		</div>
	</section>
</div>