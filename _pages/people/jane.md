---
title: "NSL Lab - Jane"
layout: personal
permalink: /people/jane/
sitemap: false
excerpt: "Personal webpage of Jane"
---
{%- assign data = site.data.people -%}
{%- assign member = data.jane -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  <!-- {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/files/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %} -->
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>

## Biography

<p>
I received my MS and PhD in Computer Science at <a href="https://www.usc.edu/">University of Southern California</a> where I was advised by <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a> and <a href="https://raghavan.usc.edu/">Prof. Barath Raghavan</a> at <a href="https://nsl.usc.edu/">Networked Systems Laboratory</a> at <a href="https://www.usc.edu/">University of Southern California</a>. 
I received my BS degree (2014) and M.S. degree (2016) in Electrical Engineering at <a href="https://www.ntu.edu.tw/english/">National Taiwan University</a>. 

My current research interest is to automate protocol code generation on specifications, in which I target on analyzing English-written ambiguous RFCs and automatically converting all types of protocols into executable and efficient codes. My broader interest includes exploring diverse network infrastructures and networked systems.

If you have any questions, please contact me at [last name]y[at]usc[dot]edu
</p>


## Teaching Experience

<p>
<em>Teaching Assistant at USC</em><br>
<b>Course:</b> Advanced Operating System, Fall 2018, <b>Instructor:</b> <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>
</p>

## Work Experience

<p>
<em>Graduate Research Assistant (August 2016 - May 2023)</em><br>
Department of Computer Science, University of Southern California.<br>
</p>

<p>
<em>Software Engineer Intern, Systems and Infrastructure (PhD)</em><br>
Meta Inc. Remote, US  · Menlo Park, CA<br>
</p>

<p></p>
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

{% bibliography -f people/jane%}

</div>
