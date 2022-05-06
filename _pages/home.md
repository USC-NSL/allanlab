---
title: "NSL Lab - Home"
layout: homelay
excerpt: "NSL Lab at University of Southern California."
sitemap: false
permalink: /
---

<h1> About </h1>

<div>

Founded in 2002, our laboratory conducts research in wired and wireless networking systems. Our past contributions have spanned research on Internet routing, peer-to-peer systems, and Internet measurement. Our current focus is on networked systems of various kinds. Our projects span the following areas:

<ol>
  <li> Data center networking and cloud-based systems </li>
  <li> Networked sensing </li>
  <li> Video distribution infrastructures </li>
  <li> Internet measurements </li>
  <li> Network performance optimization </li>
</ol>

</div>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fresco_Fawad.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Jane_Sage.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fawad_CarMap.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Weiwu_Pedestrian.png" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fawad_Netdriving.png" alt="Slide 5" />
        </div>
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Jianfeng_Galleon.png" alt="Slide 6" />
        </div>
        <div class="item">
           <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/josh_tree_of_life.png" alt="Slide 7" />
       </div>
    </div>
    <!-- <a class="carousel-control left" href="#carousel" role="button" data-slide="prev">&lsaquo;</a>
    <a class="carousel-control right" href="#carousel" role="button" data-slide="next">&rsaquo;</a> -->

  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <!-- &lsaquo; -->
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<h1> Recent Papers </h1>

<div class="publications">

{% bibliography -f papers --max 5 %}

</div>
