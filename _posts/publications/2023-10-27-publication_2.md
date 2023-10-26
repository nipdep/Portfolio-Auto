---
layout: post
title: "Semantic Segmentation for Autonomous Driving"
description: "Our work focuses on semantic segmentation for autonomous vehicles"
image: assets/images/pic06.jpg
categories: publications
type: publication
permalink: /:categories/:title
tag:
 - Deep Learning
 - Computer Vision
 - Model Optimization
 - Pytorch
---

{% assign pub = site.data.publications.publication_1 %}
<div id="main">
    <!-- One -->
    <section id="one">
        <div class="inner no-padding" >
            <div class="table-container">
            <table>
                <tr>
                    <td class="first-column"><a href="#" class="special small">Title</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.title }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small">Date</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.date }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small">Venue</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.venue }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small disable">Status</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.status }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small">Authors</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.authors }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="#" class="special small">keyword</a></td>
                    <td class="second-column"><a href="#" class="small disable">{{ pub.keyword }}</a></td>
                </tr>
                <tr>
                    <td class="first-column"><a href="{{ pub.code }}" class="button special small"><i class="fab fa-github"></i>Code</a></td>
                    <td class="second-column"><a href="{{ pub.paper }}" class="button special small"><i class="fa fa-file-pdf-o"></i>Paper</a></td>
                </tr> 
            </table>
            </div>
        </div>
    </section>
    <!-- Second -->
    <section id='second'>
        <div class="inner no-padding">
            <div>
                <h2>Abstract</h2>
                    <img src="{{ pub.image }}" width="100%" />
                    <p>{{ pub.abstract }}</p>
                    <h3>Key Contributions</h3>
                    <ul class='fa-ul'>
                        {% for key in pub.contributions %}
                        <li><i class="fa-li fa fa-check-square"></i>{{ key }}</li>
                        {% endfor %}
                    </ul>
            </div>
            <div>
                <h2>Lessons Learned</h2>
                <ul class='fa-ul'>
                    {% for less in pub.lessons %}
                    <li><i class="fa-li fa fa-check-square"></i>{{ less }}</li>
                    {% endfor %}
                </ul>
            </div>
        </div>
    </section>
</div>