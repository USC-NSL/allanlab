---
title: "NSL Lab - Yibo"
layout: personal
permalink: /people/yibo-yan/
sitemap: false
excerpt: "Personal website of Yibo Yan"
---
{%- assign data = site.data.people -%}
{%- assign member = data.yibo -%}

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

<p>I am a Ph.D. student in <a href="http://nsl.cs.usc.edu/">Networked System Lab (NSL)</a> at <a href="http://www.usc.edu">University of Southern California</a>. I am fortunate to be advised by <a href="http://seojinpark.net/">Prof. Seo Jin Park</a>. My primary research interests are in areas of <b>Distributed Systems</b>, <b>Datacenter Infrastructure</b> and <b>Massive Data Processing with Flash Burst System</b>.</p>

<p>Prior to joining USC, I completed my B.S. in Computer Science degree from University of California, Davis and my M.S in Computer Science degree from Yale University.

## Work Experience

<p>
<em>Graduate Research Assistant (Aug 2023 - present)</em>
<br>
Department of Computer Science, University of Southern California.<br>
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

{% bibliography -f people/yibo%}

</div>
