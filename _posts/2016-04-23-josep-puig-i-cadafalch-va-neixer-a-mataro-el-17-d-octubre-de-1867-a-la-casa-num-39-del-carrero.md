---
layout: post
title:  "Josep Puig i Cadafalch va néixer a Berga el 17 d’octubre de 1867 a la casa núm. 39 del Carreró"
date:   2016-04-23T11:37:00+02:00
category: articles
share: true
class: article
og: true
article: 10
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