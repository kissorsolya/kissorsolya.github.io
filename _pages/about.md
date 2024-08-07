---
permalink: /
#title: "Personal Statement"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am a **developmental sleep scientist**. My training in **Psychology** and **Computer Science** forms the foundation of my research at the intersection of data science and *neuroscience*. I earned my PhD in Cognitive Science from the [Budapest University of Technology and Economics](https://www.bme.hu/?language=en), Hungary, and my BSc in Computer Science from [Eötvös Loránd University](https://www.elte.hu/en/), Hungary.

<img src="/images/testament.png" alt="Orsolya Kiss" style="width: 250px; float: right; margin-left: 20px; margin-bottom: 10px;">

As a Research Scientist at SRI International's Center for Health Sciences, I specialize in analyzing large-scale multimodal datasets to investigate how *sleep patterns*, *brain function*, and *social connectivity* intersect to affect adolescent health. I am also passionate about **applied machine learning** and **algorithm development**. By integrating interpretable machine learning techniques with statistical analysis and signal processing methods, I aim to elucidate **the role of sleep**  in healthy development and disease. 

As part of this work, I am engaged as an investigator in the *Adolescent Behavior and Cognitive Development (ABCD) Study*, a demographically diverse multi-site consortium study that aims to determine the developmental trajectories of brain, neuropsychological, and emotional development of adolescents. 

Here are some media coverage and mentions of my work:

<ul>
  {% for article in site.data.coverage %}
    <li>
      <a href="{{ article.url }}">{{ article.title }}</a> - <em>{{ article.source }}</em> ({{ article.date }})
      <p>{{ article.summary | rreplace: 'Orsolya Kiss', '<strong>Orsolya Kiss</strong>' | replace: 'O. Kiss', '<strong>O. Kiss</strong>' }}</p>
    </li>
  {% endfor %}
</ul>


<h2>Photography</h2>

<p>Outside of my research, I’m passionate about photography, capturing moments and expressions through my lens. View some of my photos here:</p>

<ul>
  <li><a href="https://photos.app.goo.gl/Kz77oHtinwTNs7DU8" target="_blank">📸 Family Portfolio</a></li>
  <li><a href="https://photos.app.goo.gl/6YAGKW1Wz6oiLtmq7" target="_blank">🖼️ Portrait Portfolio</a></li>
</ul>

<p>These portfolios showcase my work in capturing authentic family moments and individual portraits, reflecting my passion for visual storytelling and human expression.</p>

