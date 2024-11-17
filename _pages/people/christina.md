---
title: "Christina Shin"
layout: personal
permalink: /people/christina-shin/
sitemap: false
excerpt: "Personal website of Christina"
---
{%- assign data = site.data.people -%}
{%- assign member = data.christina -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>

## Sketch

<p>
I am a fifth year Ph.D. student in <a href="https://www.cs.usc.edu/">Computer Science Department</a> at <a href="http://www.usc.edu">University of Southern California</a>. I am working with <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a> in <a href="https://nsl.usc.edu/">Networked Systems Lab (NSL)</a>. I am broadly interested in Volumetric Video Streaming, 3D Sensing, Cooperative Perception, and Autonomous Vehicle Systems. Before joining NSL, I received my B.S. and M.S. degree in Computer Science and Engineering at <a href="https://www.ewha.ac.kr/ewhaen/index.do">Ewha Womans University</a>.
</p>

## Work Experience

<p>
<em><strong>Research Assistant (Aug 2019 - Present)</strong></em><br>
<a href="https://nsl.usc.edu/">Networked Systems Lab</a>, University of Southern California, Los Angeles, USA.<br>
</p>

<p>
<em><strong>Research Intern (May 2021 - Aug 2021, May 2024 - Aug 2024)</strong></em><br>
General Motors Research and Development, Warren, USA.<br>
Mentor: Chuan Li and Fan Bai<br>
</p>

<p>
<em><strong>Research Assistant (Jan 2017 - May 2019)</strong></em><br>
<a href="https://inslab-ewha.weebly.com/">Intelligent Networked Systems Lab</a>, Ewha Womans University, Seoul, South Korea.<br>
</p>

## Publications

<div class="publications">

{% bibliography -f people/christina%}

</div>
