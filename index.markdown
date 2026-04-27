---
title: "Festival Info"
layout: single
date: 2026-04-27T11:55:00-00:00
# header:
#   overlay_image: /assets/images/BoAPoster2026.png
#   overlay_filter: 0.4
# header:
#   overlay_color: "#000"
#   overlay_filter: "0.5"
#   #overlay_image: /assets/images/unsplash-image-1.jpg
#   actions:
#     - label: "Info Download"
#       url: "/assets/docs/BOAfestivalflyer.pdf"
#   caption: "Festival flyer PDF Download"
# excerpt: "Festival Information including registration, fixtures, pitch locations, car parking and much more..."

feature_row:
  - icon_class: fa fa-info-circle
    title: "Event Info"
    excerpt: "Information for the festival, including timings, food and drink..."
    url: "/info"
    btn_label: "Read More"
    btn_class: "btn--primary disabled"
  - icon_class: fas fa-calendar-alt
    title: "Fixtures"
    excerpt: "Details of all of the fixtures being played, when and where..."
    url: "/fixtures"
    btn_label: "Read More"
    btn_class: "btn--primary disabled"  
feature_row2:
  - icon_class: fas fa-map-marker-alt
    title: "Getting Here & Car Parking"
    excerpt: "Information for getting here, car parking and payment"
    url: "/getting-hereandparking"
    btn_label: "Read More"
    btn_class: "btn--primary disabled"
  - icon_class: fas fa-users
    title: "Event Sponsors"
    excerpt: "This event couldn't happen without the kind donations from our sponsors"
    url: "/sponsors"
    btn_label: "Read More"
    btn_class: "btn--primary disabled"
---

## Welcome
We look forward to welcoming you to the Bradford on Avon Minis Festival on {{ site.festival_date }}. It is sure to be a great day of rugby, with each club, team and player following the RFU core values of Teamwork, Respect, Enjoyment, Discipline and Sportsmanship.

<!-- {% include figure 
  image_path="/assets/images/BoAPoster2026.png" 
  alt="BoA Minis Rugby Festival"
  popup=true 
%} -->

{% include feature_row %}

{% include feature_row id="feature_row2" %}
