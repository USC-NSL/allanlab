---
title: "NSL Lab - Jeongyeup"
layout: personal
permalink: /people/jpaek/
redirect_from:
 - /people/jeongyeup-paek/
 - /people/jeongyeup/
sitemap: false
excerpt: "Personal website of Jeongyeup"
---
{%- assign data = site.data.people -%}
{%- assign member = data.jpaek -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  <!-- {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{
  member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {%
  endif %} -->
  <!-- {% if member.github %} <a href="{{ member.github }}" target="_blank"><i
  class="fa fa-github-square fa-3x"></i></a> {% endif %} -->
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i
  class="fa fa-twitter-square fa-3x"></i></a> {% endif %} -->
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
  <br/>
  Jump to [Biography](#biography), [Publications](#publications), [Experiences](#work-experience).
</div>

## Biography

<p>
I am a <em>Visiting Scholar</em> at
<a href="http://www.usc.edu/">University of Southern California</a>,
<a href="http://www.cs.usc.edu">Department of Computer Science</a>.
I am also an associate professor at
<a href="http://neweng.cau.ac.kr">Chung-Ang University</a>,
<a href="http://cse.cau.ac.kr/eng/">School of Computer Science and Engineering</a>
leading the <a href="http://nsl.cau.ac.kr">Networked Systems Lab @ CAU</a>
</p>
<p>
I got my B.S. from Seoul National University in Electrical Engineering, and 
Ph.D. from University of Southern California in Computer Science.
I worked at Cisco Systems IoT Group on wireless network for Smart Grid, and
also at Hongik University as an assistant professor.
</p>

## Work Experience

<p>
<em>Visiting Scholar at University of Southern California (Aug. 2022 ~ current)</em><br>
Department of Computer Science, Networked Systems Lab.<br>
</p>

<p>
<em>Associate Professor at Chung-Ang University (Sep. 2018 ~ current)</em><br>
Department/School of Computer Science and Engineering<br>
(Assistant Prof. during Sep. 2015 ~ Aug. 2018)
</p>

<p>
<em>Assistant Professor at Hongik University (Feb. 2014 ~ Aug. 2015)</em><br>
Department of Computer Information Communication Engineering<br>
</p>

<p>
<em>Technical Leader at <a href="http://www.cisco.com">Cisco Systems</a> (July 2011 ~ Feb. 2014)</em><br>
Internet of Things Group (IoTG), San Jose, CA, USA<br>
R&D on Wireless Mesh Network for Smart Grid<br>
</p>

## Publications

<div class="publications">

<p>My publications can be found <a href="http://cau.ac.kr/~jpaek">HERE</a></p>

</div>
