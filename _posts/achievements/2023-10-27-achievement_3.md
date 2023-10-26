---
layout: post
title: "Customer Sentiment Analysis"
description: "Our team developed a sentiment analysis model to classify customer reviews as positive"
image: assets/images/pic06.jpg
categories: archievements
type: archievement
permalink: /:categories/:title
tag:
 - Deep Learning
 - Computer Vision
 - Generative AI
 - Adversarial Learning
---

{% assign arch = site.data.achievements.achievement_3 %}
<div id="main">
	<section id="one">
        <div class="inner no-padding" >
            <div class="table-container">
            <table>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Competition Title</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ arch.title }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Organizer</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ arch.organizer }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Year</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ arch.year }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Place</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ arch.place }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Team</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ arch.team }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="{{ arch.code }}" class="button special small"><i class="fab fa-github"></i> Code</a></td>
                    <td class="second-column"><a href="{{ arch.paper }}" class="button special small disable"><i class="fa fa-file-pdf-o"></i> Paper</a></td>
                </tr>
            </table>
            </div>
        </div>
    </section>
	<section id='second'>
		<div class="inner no-padding">
			<div>
				<h2>Description</h2>
				<p>{{ arch.description }}</p>
			</div>
			<div class="row">
				<div class="6u 12u$(small)">
					<h3>Technologies</h3>
					<div class='logos-container'>
                        {% for tech in arch.technologies %}
						<img src="{{site.baseurl}}/assets/images/logos/{{ tech }}.png" alt="Logo 1" class="logos">
                        {% endfor %}
					</div>
				</div>
				<div class="6u$ 12u$(small) ">
					<h3>Methodologies</h3>
					<p>
                        {% for meth in arch.methodologies %}
                        <a href="#" class="button small disable">{{ meth }}</a>
                        {% endfor %}
                    </p>
				</div>
			</div>
		</div>
	</section>
	<section id='third'>
		<div class="inner no-padding">
			<div>
				<h2>Key Achievements</h2>
                <ul class='fa-ul'>
                    {% for key in arch.archievement %}
                    <li><i class="fa-li fa fa-check-square"></i>{{ key }}</li>
                    {% endfor %}
                </ul>
			</div>
		</div>
	</section>
</div>
