---
title: "NSL Lab - Sulagna"
layout: personal
permalink: /people/sulagna-mukherjee/
sitemap: false
excerpt: "Personal webpage of Sulagna"
---
{%- assign data = site.data.people -%}
{%- assign member = data.sulagna -%}

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

<p>I am a Ph.D. candidate in the <a href="http://nsl.usc.edu/">Networked System Lab (NSL)</a> at <a href="http://www.usc.edu">University of Southern California</a>. I am lucky to be advised by <a href="https://raghavan.usc.edu/">Prof. Barath Raghavan</a>. My primary research interests have to do with Security, Human-Computer Interactions (HCI) and System Design with a focus on user centric design approaches. I am also interested in understanding how the information ecosystem is evolving with time and impacting us individually and societally. </p>
<p>Prior to joining USC, I completed my Bachelors (B.Tech) in Computer Science and Engineering at the <a href="https://iem.edu.in/">Institute of Engineering and Management (IEM), Kolkata</a>. I was advised by <a href="https://bit.ly/3yN3woH">Dr. Himadri Nath Saha</a> and worked on MANETs. </p>


## Ongoing Projects
<p>
<b>The Ghost Trilemma:</b> We look at the underlying properties that are necessary to distinguish a human-controlled account from a bot account across social media platforms. We demonstrate the impossibility of verifying these properties simultaneously online in a fully decentralized setting. We then propose a framework and suggest sketches of practical, incrementally deployable schemes to achieve an acceptable tradeoff working within the constraints. </p>

<p><b>Understanding and Shaping Usable Security as Rituals:</b> Unintentional human error is the root cause for the majority of data breaches occurring globally. We apply the concept of <em>rituals</em> as seen in the human society to inculcate better security practices in individual users. Our focus is on people who are not formally trained in Computer Science principles but are required to regularly use machines for work.</p>

<p><b>Reviewing the Evolving Nature of Internet Shutdowns:</b> An explorative study looking at the relationship between internet shutdowns and today's global information ecosystem, within the context of evolving attitudes towards censorship. <br>
</p>

## Teaching Experience

<p>
<em>Teaching Assistant at USC</em><br>
<b>Course:</b> <a href="http://www-scf.usc.edu/~csci570/">CS 570: Analysis of Algorithms</a> - Spring 2019, Summer 2018-19 <b>Instructor:</b> <a href="https://viterbi.usc.edu/directory/faculty/Shamsian/Shahriar">Shawn Shamsian</a>
<br>
<b>Course:</b> <a href="https://web-app.usc.edu/soc/syllabus/20183/29960.pdf">CS 270: Introduction to Algorithms and Theory of Computing</a> - Fall 2018, <b>Instructor:</b> <a href="https://www.ics.uci.edu/~mikes/">Michael Shindler</a>
</p>

## Work Experience

<p>
<em>Graduate Research Assistant (August 2019 - present)</em><br>
Department of Computer Science, University of Southern California.<br>
Advisor: <a href="https://raghavan.usc.edu/"> Barath Raghavan</a>
</p>

<p>
<em>Solution Integrator (Role: System Administrator in Linux) (September 2015 - July 2017)</em><br>
Ericsson India Global Services PVT. Ltd, Kolkata.<br>
</p>

<p>
<em>Summer Research Intern (May 2014 - Aug 2014)</em><br>
Indian Statistical Institute, Kolkata.<br>
Mentor: <a title="Sasthi's Website" href="https://www.isical.ac.in/~sasthi/">Sasthi C. Ghosh</a><br>
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

{% bibliography -f people/sulagna%}

</div>
