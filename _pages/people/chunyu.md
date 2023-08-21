---
title: "NSL Lab - Chunyu Xia"
layout: personal
permalink: /people/chunyu-xia/
sitemap: false
excerpt: "Personal website of Chunyu"
---
{%- assign data = site.data.people -%}
{%- assign member = data.chunyu -%}

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

<p>I am a second year CS Ph.D. student in <a href="https://nsl.usc.edu/">Networked System Lab (NSL)</a> at <a href="http://www.usc.edu">University of Southern California</a> advised by <a href="https://govindan.usc.edu/">Prof. Ramesh Govindan</a>.</p>
<p>Before joining USC, I obtained M.S. in Computer Science and Engineering at <a href="https://ucsd.edu/"> University of California, San Diego</a> advised by <a href="http://xyzhang.ucsd.edu/">Prof. Xinyu Zhang</a>, and received B.E. in Software Engineering at <a href="https://www.nju.edu.cn/EN/main.htm"> Nanjing University</a>. </p>
<p>My research interests lie in Mobile AR, IoT Security and Privacy and Vehicle-to-everything (V2X). </p>
## Work Experience

<p>
<em><strong>Graduate Research Assistant (July 2022 - Present)</strong></em><br>
<a href="https://nsl.usc.edu/">Networked Systems Lab</a>, University of Southern California, Los Angeles, USA.<br>
</p>

<p>
<em><strong>Research Intern (May 2023 - Aug 2023)</strong></em><br>
General Motors Research and Development, Warren, USA.<br>
Mentor: Chuan Li and Fan Bai<br>
</p>

## Teaching Experience

<p>
<em>Teaching Assistant at UCSD</em><br>
<b>Course:</b> <b> DSE 201, Database Management System, Winter 2022 </b> <b>, Instructor:</b> <a href="https://jacobsschool.ucsd.edu/faculty/profile?id=179">Prof. Alin Deutsch</a>
</p>
<p>
<em>Teaching Assistant at UCSD</em><br>
<b>Course:</b> <b> CSE 256, Statistical Natural Language Processing, Spring 2022 </b><b>, Instructor:</b> <a href="https://ndapa.us/">Prof. Ndapandula Nakashole</a>
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

{% bibliography -f people/chunyu%}

</div>
