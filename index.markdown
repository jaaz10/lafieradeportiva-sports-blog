---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/hero-soccer.jpg
  actions:
    - label: "Latest News"
      url: "/posts/"
excerpt: "Your ultimate destination for passionate sports coverage across all major leagues"
intro: 
  - excerpt: 'Covering the biggest matches, transfer news, and expert analysis with unmatched passion'
feature_row:
  - image_path: /assets/images/barcelona.jpg
    alt: "Barcelona"
    title: "La Liga Coverage"
    excerpt: "All the latest from Spanish football"
    url: "/la-liga/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/real-madrid-logo.png
    alt: "Real Madrid"
    title: "Champions League"
    excerpt: "European football's premier competition"
    url: "/champions-league/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/soccer-action.jpg
    alt: "Soccer Action"
    title: "Match Analysis"
    excerpt: "In-depth tactical breakdowns"
    url: "/analysis/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}

## Recent Posts

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
