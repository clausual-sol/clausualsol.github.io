---
layout: post
title:  "Joaquim Coll i Regàs va néixer a Berga l’any 1855"
date:   2016-04-21T11:37:00+02:00
category: articles
share: true
class: article
og: true
article: 02
og-type: article
---

{% assign article_data = site.data.articles | where:"id", page.article %}
{% assign article = article_data | first %}
<figure>
	<img src="{{ article.image.url }}" alt="{{ article.headline }}" class="img-responsive" />
	<figcaption>
		<p class="lead">{{ article.description}} </p>
		<p>{{ article.description-2}} </p>
		<p>{{ article.description-3}} </p>
	</figcaption>
</figure>