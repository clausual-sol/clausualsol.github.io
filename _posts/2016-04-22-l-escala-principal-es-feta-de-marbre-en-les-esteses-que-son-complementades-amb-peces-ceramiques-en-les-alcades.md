---
layout: post
title:  "L’escala principal és feta de marbre en les esteses, que són complementades amb peces ceràmiques en les alçades"
date:   2016-04-22T11:37:00+02:00
category: articles
share: true
class: article
og: true
article: 06
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