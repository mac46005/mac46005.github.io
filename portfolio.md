---
layout: page
title: Portfolio
permalink: /portfolio/
---

<h1>My Portfolio</h1>
<div class="portfolio">
    {% for project in site.projects %}
        <div class="project">
            <h2>{{ project.title }}</h2>
            <p>{{ project.description }}</p>
            <a href="{{ project.link }}">View Project</a>
        </div>
    {% endfor %}
</div>