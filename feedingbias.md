---

layout:			default
title:  		FeedingBias
type:			  page
navigation: false
details:    true

date:   		2022-01-10
excerpt: 		"Une approche mixte et multi-plateformes de l'exposition aux médias sur les réseaux sociaux "
gradient: 	2
image: 			header-1.jpg

---

**Chercheur•es impliqué•es : Gilles Bastin, Maria Castaldo, Paolo Frasca, Oana Goga, Emmanuel Marty, Jérôme Pacouret**

Le projet ANR FeedingBias vise à fournir des données et des outils analytiques pour une meilleure compréhension de l’exposition à l’information sur les réseaux sociaux et des interactions des individus avec ces informations.

Notre objectif double. Nous voulons dans un premier temps comprendre l’influence des caractéristiques sociodémographiques des utilisateurs des réseaux sociaux, de leur orientation politique et de leur niveau d'éducation algorithmique sur leur exposition à l’information, particulièrement dans le contexte de la campagne électorale pour l'élection présidentielle française de 2022. Nous voulons aussi mesurer la contribution de ces biais d'exposition et d'engagement sur la polarisation de la sphère publique.

Le projet FeedingBias est basé sur le recrutement d'un large échantillon d'utilisateurs des médias sociaux répondant à une enquête par questionnaire et nous donnant accès, de manière très contrôlée, à des informations sur leurs comptes sur Twitter, Instagram et Facebook ainsi que sur leur activité sur YouTube.

Toutes les données collectées dans le cadre de FeedingBias sont traitées selon les exigences du RGPD. L'enquête a fait l'objet d'une inscription au registre des traitements du CNRS. Le questionnaire est maintenu et hébergé par la [plateforme SCREEN](https://www.msh-alpes.fr/plateformes/screen). Les données produites dans le cadre de l'enquête sont stockées sur les serveurs de [GRICAD](https://gricad.univ-grenoble-alpes.fr/).

---

## Actualité du projet

<ul class="post-list">
        {% for post in site.categories.feedingbias offset: site.pagination + 1 %}
                <li><span class="date">{{ post.date | date: "%Y-%m-%d" }}</span> | <a class="link" href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
        {% endfor %}
</ul>
