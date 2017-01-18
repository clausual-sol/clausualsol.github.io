---
layout: post
title:  "La Mancomunitat de Catalunya, agrupació de les quatre diputacions catalanes, es va constituir l'any 1914"
date:   2016-05-05T08:37:00+02:00
category: articles
share: true
class: article
og: true
article: 13
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