---
layout: post
title:  "Learning Jekyll"
date:   2016-10-22 11:33:25 +0200
categories: news
---

<img src="/images/IMG_2060.JPG"/>
Jekyll is a great program!

{{post.excerpt}} po "</h2>" bo zraven imena bloga objavil še prvi paragraph v blogu.

"<a href="{{ post.url | prepend: site.baseurl }}">Read more ...</a>" po {{post.excerpt}} bo dodal link na blog, da bodo bralci vedeli, da je več kot prvi paragraf v blogu.

Če hočeš dodat nov font greš na google fonts, tam najdeš katerega hočeš in ga dodaš (+). Potem odpreš head.html in dodaš npr <link href="https://fonts.googleapis.com/css?family=Trirong" rel="stylesheet"> (to najdeš pri google fonts).
Potem pa še v main.css kjer to rabiš, dodaš npr. font-family: 'Trirong', serif;.

<div class="warning">Tako naredimo opozorilo.</div>