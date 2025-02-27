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
  - image_path: /assets/images/soccer-action.png
    alt: "Barcelona"
    title: "La Liga Coverage"
    excerpt: "All the latest from Spanish football"
    url: "/la-liga/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/soccer-action.png
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

## Latest Video

<div class="video-container">
  <iframe width="100%" height="400" src="https://www.youtube.com/watch?v=PucprA-yZRs&t=9s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Recent Posts

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
