---
layout: default
title: "Chão de Vidro"
description: "Projeto de reaproveitamento de vidro para criação de materiais sustentáveis."
technologies: "HTML, CSS, JavaScript"
---

<div class="project-page">

    <h1>{{ page.title }}</h1>

    <p class="project-description">
        {{ page.description }}
    </p>

    <h2>Sobre o projeto</h2>

    <p>
        O Chão de Vidro é um projeto voltado ao reaproveitamento de resíduos
        de vidro, transformando esse material em uma alternativa sustentável
        para a produção de peças e pavimentação.
    </p>

    <h2>Tecnologias</h2>

    <p>
        {{ page.technologies }}
    </p>

    <h2>Objetivo</h2>

    <p>
        Demonstrar como a tecnologia pode ser utilizada para apresentar
        soluções voltadas à sustentabilidade.
    </p>

    <a class="back-button" href="{{ '/projetos' | relative_url }}">
        ← Voltar para projetos
    </a>

</div>