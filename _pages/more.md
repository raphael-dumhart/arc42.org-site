---
title: "More..."
layout: splash

permalink: /more
header:
  #overlay_filter: rgba(15, 80, 180, 0.5)
  #overlay_image: /images/splash/publications-unsplash.jpg
  #caption: "Photo: [**Glen Carstens Peters**](https://unsplash.com/@glenncarstenspeters)"
  overlay_image: /images/splash/ukrainian-flag.jpg
  
  actions: 
   - label: "Docs+Tipps"
     url: https://docs.arc42.org
   - label: "FAQ"
     url: https://faq.arc42.org
   - label: "Books"
     url: /books
   - label: "Articles"
     url: "/articles"
   - label: "Videos"
     url: /videos  
   - label: "Talks"
     url: /talks
   - label: "Help Ukraine"  
     url: https://ukrainewar.carrd.co

excerpt: "we talk and write about architecture...<span style='font-size:80px;'>&#128521;</span>"


docs_feature:
  - image_path: /images/publications/docs-feature.png
    alt: "Docs"
    title: "Doku und Tipps"
    excerpt: 'Extensive documentation, more than hundred practical tips for using arc42. 
    For all kinds of systems, small and large teams, all kinds of tools.'
    url: https://docs.arc42.org
    btn_label: "zu Doku & Tipps ..."
    btn_class: "btn--primary"

faq_feature:
  - image_path: /images/publications/faq-feature.png
    alt: "FAQ"
    title: "FAQs"
    excerpt: 'Frequently asked questions with answers, concerning methodical approaches, arc42-sections, agility, tools and more.'
    url: https://faq.arc42.org
    btn_label: "zu den FAQs ..."
    btn_class: "btn--primary"

books_feature:
  - image_path: /images/publications/book-feature.png
    alt: "books"
    title: "Books"
    excerpt: 'Together we authored more than 25 books, their topics ranging from requirements engineering, business-analysis, architecture, documentation to patterns.'
    url: /books
    btn_label: "more ..."
    btn_class: "btn--primary"


videos_feature:
  - image_path: /images/publications/video-feature.png
    alt: "Videos"
    title: "Videos"
    excerpt: 'Several of our conference talks have been recorded. A few times we tried to produce videos ourselves... Since 2020, arc42 hosts its own [Youtube-channel](https://www.youtube.com/arc42-video/)... '
    url: /videos
    btn_label: "more ..."
    btn_class: "btn--primary"

articles_feature:
  - image_path: /images/publications/article-feature.png
    alt: "articles"
    title: "Articles"
    excerpt: "More than a hundred articles in various publications (aah - most if that in German)."
    url: /articles
    btn_label: "more ..."
    btn_class: "btn--primary"

talks_feature:
  - image_path: /images/publications/talks-feature.jpeg
    alt: "Vorträge"
    title: "Vorträge"
    excerpt: 'Wir haben über 25 Bücher geschrieben, von der Anforderungsklärung, Business-Analyse, Architektur, Dokumentation, Verhaltensmuster (Knigge) bis zu Patterns'
    url: /talks
    btn_label: "mehr dazu ..."
    btn_class: "btn--primary"


---

{% include feature_row id="docs_feature" type="left" %}
{% include feature_row id="faq_feature" type="right" %}

{% include feature_row id="books_feature" type="left" %}

{% include feature_row id="articles_feature" type="right" %}

{% include feature_row id="videos_feature" type="left" %}

{% include feature_row id="talks_feature" type="right" %}



 