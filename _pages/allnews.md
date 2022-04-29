---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---

# News

<!-- <div>

{% for article in site.data.news %}
<p>{{ article.date }} </p> <br>
<p><em>{{ article.headline | markdownify}}</em></p>
{% endfor %}

</div> -->

<div id="newsid">
{% for article in site.data.news limit:9 %}
<p>{{ article.date }}<br>{{ article.headline | markdownify}}</p>
{% endfor %}
</div>
