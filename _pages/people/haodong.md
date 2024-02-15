---
title: "Haodong Wang"
layout: personal
permalink: /people/haodong-wang/
sitemap: false
excerpt: "Personal website of Haodong"
---
{%- assign data = site.data.people -%}
{%- assign member = data.haodong -%}

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
  <br/>
  Jump to [Biography](#biography), [Publications](#publications), [Experiences](#work-experience).
</div>

## Biography

<p>I am a first-year Ph.D. student in <a href="http://nsl.usc.edu/">Networked System Lab (NSL)</a> at <a href="http://www.usc.edu">University of Southern California</a>. I am honored to work with <a href="https://www.harsha.usc.edu/">Prof. Harsha Madhyastha</a> and <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>. My research interests include <b>Volumetric Video</b>, <b>Video Analytics</b> and <b>Systems for Machine Learning</b>.</p>
<p>Prior to joining USC, I completed my pre-doctoral M.S. in Computer Science at the <a href="https://cs.uchicago.edu/"> University of Chicago </a> and my B.S. in Computer Science at <a href="https://sai.pku.edu.cn/znxyenglish/index.htm"> Peking University </a>.</p>

## Work Experience

<p>
<em>Graduate Research Assistant (August 2023 - present)</em><br>
Department of Computer Science, University of Southern California<br>
Advisor: <a title="Harsha's Website" href="https://www.harsha.usc.edu/">Harsha Madhyastha</a>, <a title="Ramesh's Website" href="https://govindan.usc.edu/">Ramesh Govindan</a><br>
</p>

<p>
<em>Graduate Research Assistant (September 2021 - May 2023)</em><br>
Department of Computer Science, University of Chicago <br>
Advisor: <a title="Junchen's Website" href="https://people.cs.uchicago.edu/~junchenj/">Junchen Jiang</a><br>
</p>

## Teaching Experience

<p>
<em>Teaching Assistant at the University of Chicago</em><br>
<b>Course:</b> <a href="https://mpcs-courses.cs.uchicago.edu/2022-23/autumn/courses/mpcs-51046-1">MPCS 51046: Intermediate Python Programming, Fall 2022</a><br>
<b>Course:</b> <a href="https://mpcs-courses.cs.uchicago.edu/2022-23/winter/courses/mpcs-51044-1">MPCS 51044: C++ for Advanced Programmers, Winter 2022</a><br>
</p>

{% if member.awards %}
## Awards
{% endif %}

{% for award in member.awards %}
<ul style="overflow: hidden">
<li> {{ award }} </li>
</ul>
{% endfor %}

## Publications

<div class="publications">

{% bibliography -f people/haodong%}

</div>
