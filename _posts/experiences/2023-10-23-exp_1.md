---
layout: detail
title: "Machine Learning Engineer"
description: "In my role as a Machine Learning Engineer at XYZ Tech Solutions"
image: assets/images/pic06.jpg
categories: experiences
type: experience
permalink: /:categories/:title
---

{% assign exp = site.data.experiences.exp_1 %}
<div id="main">
	<section id='second'>
		<div class="inner no-padding">
            <div class="tag-container">
                    <ul class="actions">
                        <li><a href="#" class="button special small disable">Job Title</a><a href="#" class="button small disable">{{ exp.title }}</a></li>
                        <li><a href="#" class="button special small disable">Company</a><a href="#" class="button small disable">{{ exp.company }}</a></li>
						<li><a href="#" class="button special small disable">Employment Type</a><a href="#" class="button small disable">{{ exp.employment_type }}</a></li>
                        <li><a href="#" class="button special small disable">Employment Period</a><a href="#" class="button small disable">{{ exp.employment_period }}</a></li>
						<li><a href="#" class="button special small disable">Location</a><a href="#" class="button small disable">{{ exp.location }}</a></li>
                    </ul>
            </div>
			<div>
				<h2>Description</h2>
				<p>{{ exp.description }}</p>
			</div>
		</div>
	</section>
	<section id='third'>
		<div class="inner no-padding">
			<div>
				<h2>Collaborated Projects</h2>
				{% for prj in exp.projects %}
				<div>
					<h3>{{ prj.title }}</h3>
					<p>{{ prj.description }}</p>
					<div class="row">
						<div class="6u 12u$(small)">
							<h4>Technologies</h4>
							<div class='logos-container'>
								{% for tech in prj.technologies %}
								<img src="{{site.baseurl}}/assets/images/logos/{{ tech }}.png" alt="Logo 1" class="logos">
								{% endfor %}
							</div>
						</div>
						<div class="6u$ 12u$(small) ">
							<h4>Methodologies</h4>
							<p>
								{% for meth in prj.methodologies %}
								<a href="#" class="button small disable">{{ meth }}</a>
								{% endfor %}
							</p>
						</div>
					</div>
				</div>
				{% endfor %}
			</div>
		</div>
		<div class="inner no-padding">
			<div>
				<h2>Key Achievements</h2>
                <ul class='fa-ul'>
					{% for key in exp.archievement %}
                    <li><i class="fa-li fa fa-check-square"></i>{{ key }}</li>
					{% endfor %}
                </ul>
			</div>
		</div>
	</section>
</div>
