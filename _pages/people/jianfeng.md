---
title: "Jianfeng Wang"
layout: personal
permalink: /people/jianfeng-wang/
sitemap: false
excerpt: "Personal website of Jianfeng"
---
{%- assign data = site.data.people -%}
{%- assign member = data.jianfeng -%}

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
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}
  </ul>
</div>

## Biography

<p>I am a Ph.D. candidate in the <a href="https://minghsiehee.usc.edu/">ECE department</a> at at <a href="http://www.usc.edu">University of Southern California</a>. I am fortunate to work with <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a> and <a href="https://raghavan.usc.edu/">Prof. Barath Raghavan</a> in <a href="http://nsl.cs.usc.edu/">Networked System Lab (NSL)</a>.
<p>Prior to joining USC, I obtained my B.S. degree in Electrical Engineering and B.A. degree in Economics at <a href="http://english.pku.edu.cn/">Peking University</a>.</p>
<p>I am interested in Computer Networking and System research including software-defined networking (SDN), network function virtualization (NFV), and high-performance cloud/edge computing.</p>

## Work Experience

<p>
<em>Graduate Research Assistant (2017 - present)</em><br>
Department of Computer Science, University of Southern California.<br>
</p>

<p>
<em>Research Intern (May 2020 - Aug 2020)</em><br>
Google Inc., New York City, NY.<br>
Mentor: <a href="http://neal.nu/">Neal Cardwell</a><br>
</p>

<p>
<em>SWE Intern (May 2019 - Aug 2019)</em><br>
Google Inc., Seattle, WA.<br>
Mentor: <a href="https://www.linkedin.com/in/tbansal-0998216">Tarun Bansal</a><br>
</p>

## Teaching Experience
<p>
<b>Course:</b> CSCI 402: Operating Systems, Fall 2022
</p>

## Publications

<div class="publications">

{% bibliography -f people/jianfeng%}

</div>

{% if member.awards %}
## Awards
{% endif %}

{% for award in member.awards %}
<ul style="overflow: hidden">
<li> {{ award }} </li>
</ul>
{% endfor %}
