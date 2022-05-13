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
        <li data-target="#carousel" data-slide-to="7"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fresco_Fawad.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Rajrup_KinectStream.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Jane_Sage.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fawad_CarMap.png" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Weiwu_Pedestrian.png" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Fawad_Netdriving.png" alt="Slide 6" />
        </div>
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/Jianfeng_Galleon.png" alt="Slide 7" />
        </div>
        <div class="item">
           <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/josh_tree_of_life.png" alt="Slide 8" />
       </div>
    </div>
    <!-- <a class="carousel-control left" href="#carousel" role="button" data-slide="prev">&lsaquo;</a>
    <a class="carousel-control right" href="#carousel" role="button" data-slide="next">&rsaquo;</a> -->

  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" stroke="black" stroke-width="3" fill="white" class="bi bi-arrow-left" viewBox="0 0 16 16">
      <path fill-rule="evenodd" d="M15 8a.5.5 0 0 0-.5-.5H2.707l3.147-3.146a.5.5 0 1 0-.708-.708l-4 4a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708-.708L2.707 8.5H14.5A.5.5 0 0 0 15 8z"/>
    </svg>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <!-- <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span> -->
    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" stroke="black" stroke-width="3" fill="white" class="bi bi-arrow-right" viewBox="0 0 16 16">
      <path fill-rule="evenodd" d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"/>
    </svg>
  </a>
</div>

<h1> Recent Papers </h1>

<div class="publications">

{% bibliography -f papers --max 5 %}

</div>
