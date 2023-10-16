---

layout:			default
title:  		GenderedNews
type:			  page
navigation: false
details:    true

date:   		2022-02-11
excerpt: 		"Une approche computationnelle des inégalités de genre dans les médias français "
gradient: 	2
image: 			header-1.jpg

---

GenderedNews mesure de manière computationnelle les inégalités de mention et de citation des hommes et des femmes dans les articles ou contenus publiés par les principaux médias français, ainsi que certains aspects des stéréotypes de genre dans ces médias. Ces mesures permettent de rendre visible la part très importante des contenus des médias consacrée aux hommes, que ce soit en termes de mentions (le fait de parler d’hommes dans les articles) ou de citations (le fait de donner la parole à des hommes). Elles permettent aussi de visualiser les différences entre médias et l’évolution de ces pratiques dans le temps.

GenderedNews est un projet de recherche de l’Université Grenoble Alpes. Il associe la chaire Société algorithmique et la chaire Intelligence Artificielle & Language de MIAI. Ce projet est mené en partenariat avec les rédactions de Mediapart et de l'AFP avec lesquelles nous travaillons aussi à essayer d'expliquer ces écarts à partir d'entretiens dans le cadre de la thèse d'Ange Richard.

Pour plus d'informations, voir le [site web du projet](https://gendered-news.imag.fr/).

---


## Chercheur•es impliqué•es

Gilles Bastin, Professeur de sociologie, Pacte • François Portet, Professeur d'informatique, LIG • Ange Richard, doctorante à Pacte et au LIG

---

## Actualité du projet

<ul class="post-list">
        {% for post in site.categories.genderednews offset: site.pagination + 1 %}
                <li><span class="date">{{ post.date | date: "%Y-%m-%d" }}</span> | <a class="link" href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
        {% endfor %}
</ul>

## Publications

1. Gilles Bastin. « Gender Imbalance in the Media: Time Lag or Hysteresis?—French Newspapers, Gender Parity Shocks, and the Long and Winding Road to the Demasculinization of Political Reporting (1990–2020) ». The International Journal of Press/Politics, 2022. [https://shs.hal.science/halshs-03885693](https://shs.hal.science/halshs-03885693).
2. Ange Richard, Gilles Bastin, François Portet, « GenderedNews: Une approche computationnelle des écarts de représentation des genres dans la presse française », 2022. [https://arxiv.org/abs/2202.05682v2](https://arxiv.org/abs/2202.05682v2).
