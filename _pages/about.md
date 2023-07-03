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

groups: [staff, support, admin, affiliated]
staff:
  title: Staff
  people:
    - name: Barbara Plank
      description: Prof. Dr. and Chair for AI and Computational Linguistics, Lead MaiNLP and Co-director CIS
      website: https://bplank.github.io/
      picture: barbara.jpg
    - name: Siyao (Logan) Peng
      description: Postdoc (2023–)
      website: https://logan-siyao-peng.github.io/
      picture: logan.jpeg
    - name: Leon Weber
      description: Postdoc (2022–)
      website: https://leonweber.me/
      picture: leon.png
    - name: Robert Litschko
      description: Postdoc (2022–)
      website: https://rlitschk.github.io/
      picture: robert.png
    - name: Katya Artemova
      description: Postdoc (2022–)
      website: https://scholar.google.com/citations?hl=en&user=G0lCb3wAAAAJ
      picture: katya.jpg
    - name: Xinpeng Wang
      description: PhD student (2022–)
      website: https://xinpeng-wang.github.io/
      picture: xinpeng.jpg
    - name: Verena Blaschke
      description: PhD student (2022–)
      website: https://verenablaschke.github.io/
      picture: verena.jpg
    - name: Shengqiang Zhang
      description: Affiliated PhD student (2022–)
      website: https://shengqiang-zhang.github.io/
      picture: shengqiang.jpg
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
support:
  title: Support Staff
  people:
    - name: Barbara Kovačić
      description: student assistant (2023–)
      picture: barbarak.png
    - name: Zihang Sun
      description: student assistant (2023–)
      picture: zihang.png
    - name: Marie Kolm
      description: student assistant (2023–)
      picture: marie.jpeg
    - name: Huangyan Shan
      description: student assistant (2023–)
      picture: huangyan.jpg
admin:
  title: Administrative Staff
  people:
    - name: Paravee Jungbauer
      description: Assistant
      picture: paravee.jpg
    - name: Mohiuddin Forhad
      description: Technician
      picture: mohiuddin.jpg
affiliated:
  title: Affiliated researchers, co-supervisors, guest researchers
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
      picture: raquel.png
    - name: Wilker Aziz
      description: Assistant Professor at UvA
      website: https://wilkeraziz.github.io/
      picture: wilker.png
    - name: Alberto Muñoz-Ortiz
      description: Guest researcher (2023), Universidade da Coruña
      website: https://amunozo.github.io/  
      picture: alberto.jpg

---

Welcome!
We are the Munich AI & NLP (MaiNLP) research lab at the [Center for Information and Language Processing (CIS)](https://www.cis.lmu.de/) at LMU Munich. 
We carry out research in Natural Language Processing, an interdisciplinary subdiscipline of Artificial Intelligence at the interface of computer science, linguistics and cognitive science. 
In broad terms, our aim is to make NLP models more robust, so that they can deal better with underlying shifts in data due to language variation.

<div class="projects">
  <h2 class="category">News</h2>
   <ul>
    <li> Dr. Lea Frermann (University of Melbourne) will be giving an on-site <a href="/events/#2023-07-14-lea-frermann">talk</a> on July 14, 2023</li>
    <li>Prof. Barbara Plank participated in a hearing at the Bavarian parliament on ChatGPT in academia <a href="https://www.bayern.landtag.de/aktuelles/aus-den-ausschuessen/wissenschaftsausschuss-anhoerung-chancen-und-risiken-von-ki-im-wissenschaftsbetrieb">Anhörung zur Künstlichen Intelligenz im Wissenschaftsbetrieb</a> on June 23, 2023</li>
    <li>Dr. Yves Scherrer (University of Helsinki) will be giving an on-site <a href="/events/#2023-06-05-yves-scherrer">talk</a> on June 5, 2023</li>
    <li>Dr. Michael A. Hedderich (Cornell University) will be giving an on-site <a href="/events/#2023-05-15-michael-hedderich">talk</a> on May 15, 2023</li>
    <li>Dr. Saif Mohammad (NRC Canada) will be giving an on-site <a href="/events/#2023-05-08-saif-mohammad">talk</a> on May 8, 2023</li>
    <li>April 25, 2023: Barbara Plank's ERC and our MaiNLP lab research is featuring in the LMU University news! <a href="https://www.lmu.de/en/newsroom/news-overview/news/language-technologies-for-digital-inclusion.html">"Language technologies for digital inclusion"</a> (available also in <a href="https://www.lmu.de/de/newsroom/newsuebersicht/news/sprachtechnologien-fuer-die-digitale-teilhabe.html">German: "Sprachtechnologien für die digitale Teilhabe"</a>)</li>
    <li>Barbara Plank, Katya Artemova and Verena Blaschke will present and be panel mentor at the Munich <a href="https://www.eventbrite.de/e/get-together-women-in-nlp-tickets-616473698427">Women in NLP get-together</a> on April 24</li>
  </ul>

  {%- for group in page.groups -%}
  <h2 class="category">{{page.[group].title}}</h2>
    <div class="grid">
      {%- for person in page.[group].people -%}
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
              {{person.description}}
              <!-- <p style="margin-bottom: 0rem;">{{person.description}}</p> 
              <ul class="network-icon" aria-hidden="true">
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
      {%- endfor -%}
    </div>
  {%- endfor -%}

  <h2 class="category">External PhDs</h2>
   <ul>
     <li><a href="https://patschw.github.io/">Patrick Schwabl</a> (2022–), external PhD student</li>
  </ul>
  
  <h2 class="category">Support staff and student assistants for teaching</h2>
   <ul>
    <li>Chaeeun Lee (2022–)</li>
    <li>Bolei Ma (2022–)</li>
    <li>Ercong Nie (2022–)</li>
    <li>Shija Zhou (2022–)</li>
  </ul>
  

  
 <!-- <h2 class="category">Prior MaiNLP lab members</h2>
  <ul>
    <li>Anna Barwig, student assistant for research project (2022-2023)</li>
  </ul>
  --> 
  <h2 class="category">You?</h2>
  Join us! <a href="/jobs">→Open positions</a>

  <h2 class="category">MaiNLP resources and code</h2>
  You can find resources (data, code, repositories) released by MaiNLP lab members <a href="https://github.com/mainlp/">→ on our github page</a> and <a href="https://huggingface.co/mainlp">on our huggingface page</a>

  <h2 class="category">Funding</h2>
  Our research is supported by and we thank our sponsors:
  <ul>
    <li>European Research Council (ERC)</li>
    <li>Danmarks Frie Forskningsfond (DFF)</li>
    <li>Freistaat Bayern</li>
    <li>Bayerisches Forschungsinstitut für Digitale Transformation</li>
    <li>Munich Center for Machine Learning (MCML)</li>
  </ul>

 <!-- TODO <img src="MCML_Logo.jpg" alt="MCML logo"/> -->
  
  <h2 class="category">Find us</h2>
  We are located at Akademiestraße 7, 80799 Munich, Germany.<br/>

  <a href="https://github.com/mainlp"><i class="fab fa-github"></i> MaiNLP</a><br/>
  <a href="https://twitter.com/MaiNLPlab"><i class="fab fa-twitter"></i> MaiNLPlab</a><br/>
  <a href="https://twitter.com/CisLMU"><i class="fab fa-twitter"></i> CisLMU</a>

</div>
