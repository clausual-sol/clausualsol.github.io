---
layout: post
title:  "Des de molt jove, Josep Puig i Cadafalch, participa en la política catalanista"
date:   2016-05-05T08:37:00+02:00
category: articles
share: true
class: article
og: true
article: 12
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