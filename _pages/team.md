---
title: "NSL Lab - Team"
layout: gridlay
excerpt: "NSL Lab: Team members"
sitemap: false
permalink: /team/
---

<!-- # Group Members -->
<!-- **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!** -->


Jump to [Faculty](#faculty), [Current Students](#current-students), [Alumni](#alumni).

<!----------------------------------------------------------------------------------------------------------------------------------------->
## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.team.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {%- include socialmedia.html -%}
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  <!-- {% for education in member.education %}
    <li>{{ education }}</li>
  {% endfor %} -->

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!----------------------------------------------------------------------------------------------------------------------------------------->
## Current Students
{% assign number_printed = 0 %}
{% assign my_array = site.data.team.current-students | sort: "lastname" %}
<!-- Inspect a variable in liquid -->
<!-- {{ my_array[0] | inspect }} -->

{% for member in my_array%}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">

  {% if member.photo != null %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  
  <h4>{{ member.name }}</h4>
  {%- include socialmedia.html -%}
  <i>{{ member.info }}</i><!--<br>email: <{{ member.email }}></i> -->
  {% if member.advisor.size == 1 %}
  Advisor: <i>{{ member.advisor }}</i>
  {% endif %}

  {% if member.advisor.size > 1 %} <!-- Generally a student is advised by max of 2 professors -->
  Advisor: <i>{{ member.advisor[0] }}</i>, <i>{{ member.advisor[1] }}</i>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!----------------------------------------------------------------------------------------------------------------------------------------->
{% if site.data.team.other-students.size > 0 %}
## Master and Bachelor Students
{% endif %}
{% assign number_printed = 0 %}
{% for member in site.data.team.other-students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  <!-- {% for education in member.education %}
    <li>{{ education }}</li>
  {% endfor %} -->

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!----------------------------------------------------------------------------------------------------------------------------------------->
## Alumni
<div class="row">
{% for member in site.data.alumni %}
<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i> {{ member.role }}</i>
</div>
{% endfor %}
</div>

<!----------------------------------------------------------------------------------------------------------------------------------------->
<!-- ## Former visitors, BSc/ MSc students

<div class="row">
<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div> -->
