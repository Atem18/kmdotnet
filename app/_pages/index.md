---
title: Welcome to my personnal network
layout: splash
permalink: "/"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/assets/images/home.jpg"
  cta_label: About me
  cta_url: "/about/"
excerpt: You will find here all the stuff I love, personnal stuff, technical stuff
  and so much more
intro:
- excerpt: Why not discover one thing of each domain I love ?
feature_row:
- image_path: "/assets/images/technology.jpg"
  alt: technology
  title: Technology
  excerpt: DevOps, Linux, Network, DBA, etc.
  url: "/wiki/"
  btn_label: Read about technology
  btn_class: btn--inverse
- image_path: "/assets/images/games.jpg"
  alt: games
  title: Games
  excerpt: Magic, E-sport, Guild of Gamers, etc.
  url: "/games/"
  btn_label: Read about games
  btn_class: btn--inverse
- image_path: "/assets/images/writing.jpg"
  alt: books
  title: Books
  excerpt: Reading, writing, etc.
  url: "/books/"
  btn_label: Read about books
  btn_class: btn--inverse

---
{% include feature_row id="intro" type="center" %}

{% include feature_row %}