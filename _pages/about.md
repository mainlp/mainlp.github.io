---
layout: about
title: Home
permalink: /
subtitle: 

profile:
  align: right
  image: mainlp-logo-500.png
  image_circular: false
  address: 

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page

groups: [staff, affiliated]
staff:
  title: Staff
  people:
    - name: Barbara Plank
      description: Prof. Dr. and Chair for AI and Computational Linguistics
      website: https://bplank.github.io/
      picture: barbara.jpg
    - name: Sabine Greser
      description: Secretary
    - name: Robert Litschko
      description: Postdoc (2022–)
      website: https://rlitschk.github.io/
    - name: Katya Artemova
      description: Postdoc (2022–)
      website: https://scholar.google.com/citations?hl=en&user=G0lCb3wAAAAJ
      picture: katya.jpg
    - name: Verena Blaschke
      description: PhD student (2022–)
      website: https://verenablaschke.github.io/
      picture: verena.jpg
    - name: Joris Baan
      description: Affiliated PhD student (2021–)
      website: https://jorisbaan.nl/
      picture: joris.jpg
    - name: Elisa Bassignana
      description: Affiliated PhD student (2020–)
      website: https://elisabassignana.github.io/
      picture: elisa.jpg
    - name: Mike Zhang
      description: Affiliated PhD student (2020–)
      website: https://jjzha.github.io/
      picture: mike.jpg
    - name: Max Müller-Eberstein
      description: Affiliated PhD student (2020–)
      website: https://personads.me/
      picture: max.jpg
affiliated:
  title: Affiliated researchers and/or co-supervisors
  people:
    - name: Maria Barrett
      description: Postdoc at ITU
      website: https://mariabarrett.github.io/
      picture: maria.jpg
    - name: Rob van der Goot
      description: Assistant professor at ITU
      website: https://robvanderg.github.io/
      picture: rob.jpg
    - name: Raquel Fernández
      description: Professor at UvA
      website: https://staff.fnwi.uva.nl/r.fernandezrovira/
---

Welcome!
We are the Munich AI & NLP (MaiNLP) research lab at the [Center for Information and Language Processing (CIS)](https://www.cis.lmu.de/) at LMU Munich. 
We carry out research in Natural Language Processing, an interdisciplinary subdiscipline of Artificial Intelligence at the interface of computer science, linguistics and cognitive science. 
In broad terms, our aim is to make NLP models more robust, so that they can deal better with underlying shifts in data due to language variation.

<div class="projects">
  {%- for group in page.groups -%}
  <h2 class="category">{{page.[group].title}}</h2>
    <div class="grid">
      {%- for person in page.[group].people -%}
        <div class="container">
          <article class="grid-item card">
            {% if person.picture -%}
              <img class="avatar" src="/assets/img/{{person.picture}}" alt="Portrait ({{person.name}})" width="auto" height="auto">
            {%- else -%}
              <img class="avatar" src="/assets/img/mainlp-logo-500.png" alt="Portrait ({{person.name}})" width="auto" height="auto">
            {%- endif -%}
          <div class="card-body">
            <!-- <h2 class="card-title">{{person.name}}</h2> -->
            <h2 class="card-title">
              {% if person.website -%}
                <a href="{{person.website}}">{{person.name}}</a>
              {%- else -%}
                {{person.name}}
              {%- endif -%}
            </h2>
            <div class="card-text">
              <!-- <p style="margin-bottom: 0rem;">{{person.description}}</p> -->
              {{person.description}}
            <!-- <ul class="network-icon" aria-hidden="true">
              {% if person.website -%}
                <li><a href="{{person.website}}"><i class="fas fa-globe"></i></a></li>
              {%- endif -%}
              {% if person.email -%}
                <li><a role="button" class="email" style="color: var(--global-theme-color)"><i class="fas fa-envelope"></i></a></li>
              {%- endif -%}
              {% if person.googlescholar -%}
                <li><a href="{{person.googlescholar}}"><i class="ai ai-google-scholar"></i></a></li>
              {%- endif -%}
              {% if person.github -%}
                <li><a href="{{person.github}}"><i class="fab fa-github"></i></a></li>
              {%- endif -%}
              {% if person.twitter -%}
                <li><a href="{{person.twitter}}"><i class="fab fa-twitter"></i></a></li>
              {%- endif -%}
            </ul>
            {% if person.email -%}
              <div class="email hidden">
                <p>{{ person.email }}</p>
              </div>
            {%- endif -%} -->
              </div>
            </div>
          </article>
        </div>
      {%- endfor -%}
    </div>
  {%- endfor -%}
  <h2 class="category">You?</h2>
  Join us! <a href="/jobs">Open positions</a>

  <h2 class="category">Find us!</h2>
  We're located at Akademiestraße 7, 80799 Munich, Germany.<br/>

  <a href="https://twitter.com/MaiNLPlab"><i class="fab fa-twitter"></i> MaiNLPlab</a><br/>
  <a href="https://twitter.com/CisLMU"><i class="fab fa-twitter"></i> CisLMU</a>

</div>