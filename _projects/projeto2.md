---
layout: default
title: "BeatFinder"
description: "Site desenvolvido para trabalhar com música e interação."
technologies: "HTML, CSS e JavaScript"
---

<div class="project-page">

    <h1>{{ page.title }}</h1>

    <p class="project-description">
        {{ page.description }}
    </p>

    <h2>Sobre o projeto</h2>

    <p>
        O BeatFinder é um projeto de desenvolvimento web criado para
        trabalhar com música, áudio e interação com o usuário.
    </p>

    <h2>Tecnologias</h2>

    <p>
        {{ page.technologies }}
    </p>

    <h2>Objetivo</h2>

    <p>
        Desenvolver conhecimentos em JavaScript, manipulação de elementos
        HTML e reprodução de áudio.
    </p>

    <a class="back-button" href="{{ '/projetos' | relative_url }}">
        ← Voltar para projetos
    </a>

</div>