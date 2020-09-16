---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Selected Publications
  * (09/2020) I serve as a PC member in the 26th Asia-Pacific Software Engineering Conference (APSEC) 2020. My first official academic service.
  * (09/2020) :star: Our paper “A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices” is accepted by IEEE TIFS 2020.
  * (08/2020) :star: Our paper “SeqMobile: An Efficient Sequence-Based Malware Detection System Using RNN on Mobile Devices” is accepted by ICECCS 2020.
  * (08/2020) :clap: I submitted my thesis.