---
layout: default
permalink: /services/
title: Services
featured: true
---

<div class="container">
    
    <div class="main-content">
	        <section class="featured-posts">

            <div class="section-title">
                <h2><span>Our Services</span></h2>
            </div>

            <div class="row listfeaturedtag">

            {% for post in site.posts %}

                {% if post.featured == true %}
					{% if post.services == true %}
						{% include featuredbox.html %}
					{% endif %}
                {% endif %}

            {% endfor %}

            </div>

        </section>
	
</div>
</div>