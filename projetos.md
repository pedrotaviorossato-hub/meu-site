---
layout: default
title: Projetos
---

<section class="projects-page">

    <h1>Meus projetos</h1>

    <p class="projects-intro">
        Alguns projetos desenvolvidos durante meus estudos.
    </p>

    <div class="projects">

        {% for projeto in site.projects %}

        <div class="project">

            <h2>{{ projeto.title }}</h2>

            <p>
                {{ projeto.description }}
            </p>

            <p class="technologies">
                {{ projeto.technologies }}
            </p>

            <a href="{{ projeto.url | relative_url }}">
                Ver projeto
            </a>

        </div>

        {% endfor %}

    </div>

</section>