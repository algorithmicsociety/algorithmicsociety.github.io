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

Le projet FeedingBias est financé par l'Agence Nationale de la Recherche. Il vise à fournir des données et des outils permettant une meilleure compréhension de l’exposition à l’information sur les réseaux sociaux et des interactions des individus avec ces informations (voir plus bas).

Ce projet est basé sur une démarche de science participative. Les plateformes des réseaux sociaux comme Facebook ou Twitter refusent en effet de plus en plus l'accès à leurs données aux chercheurs. Pour contourner cet obstacle, nous proposons aux participants à cette enquête — en plus de répondre à quelques questions — de nous donner accès, de manière très contrôlée, à des informations sur leur activité sur Twitter, Instagram, Facebook et YouTube.

Nous ne collectons que des informations sur l'accès à l'information médiatique, en aucun cas des données concernant les relations personnelles et la vie privée des individus. Par ailleurs nous anonymisons strictement toutes les données que nous collectons. En contrepartie de votre participation à l'enquête, vous aurez la possibilité de gagner un prix de 50€. Merci par avance de votre contribution !

<a href="https://enquetes-screen.msh-alpes.fr/index.php/451574?lang=fr"><img src="https://algorithmicsociety.github.io/images/jeparticipe_bouton.jpg" height="60" class="center"></a>

Toutes les données collectées dans le cadre de FeedingBias sont traitées selon les exigences du Règlement Général pour la Protection des Données. L'enquête a fait l'objet d'une inscription au registre des traitements du Centre National de la Recherche Scientifique. Le questionnaire est maintenu et hébergé par la [plateforme SCREEN](https://www.msh-alpes.fr/plateformes/screen). Les données produites dans le cadre de l'enquête sont stockées sur les serveurs de [GRICAD](https://gricad.univ-grenoble-alpes.fr/).

_**Plus de détails sur l'objectif scientifique de l'enquête.** Nous voulons dans un premier temps comprendre l’influence des caractéristiques sociodémographiques des individus, de leur orientation politique et de leur niveau d'éducation algorithmique sur leur exposition à l’information sur les réseaux sociaux (le fait de voir des informations circuler sur ces réseaux) et sur leur engagement avec l'information (le fait de liker, commenter ou reposter de l'information). Nous voulons aussi mesurer la contribution de ces biais d'exposition et d'engagement sur la polarisation de la sphère publique._

---

## **Chercheur•es impliqué•es**

**Gilles Bastin** (Sciences Po Grenoble / Pacte). Gilles Bastin est Professeur de sociologie. Il coordonne l'ensemble du projet du projet. [Plus d'infos sur ses recherches](gillesbastin.github.io/). Contact : [gilles.bastin@iepg.fr](mailto:gilles.bastin@iepg.fr).
<hr>

**Paolo Frasca** (CNRS / GIPSA). Paolo Frasca est Chargé de recherche au CNRS. Il coordonne la collecte et l'analyse de données sur la médiation et la réception des informations sur YouTube. [Plus d'infos sur ses recherches](http://www.gipsa-lab.grenoble-inp.fr/~paolo.frasca/). Contact : [paolo.frasca@gipsa-lab.grenoble-inp.fr](paolo.frasca@gipsa-lab.grenoble-inp.fr).
<hr>

**Oana Goga** (CNRS / LIX-polytechnique). Oana Goga est Chargée de recherche au CNRS. Elle coordonne la collecte et l'analyse de données sur la médiation et la réception des informations sur YouTube. [Plus d'infos sur ses recherches](lix.polytechnique.fr/~goga/). Contact : [oana.goga@cnrs.fr](mailto:oana.goga@cnrs.fr).
<hr>

**Emmanuel Marty** (UGA / Gresec). Emmanuel Marty est Maître de conférences en sciences de l'information et de la communication. Il coordonne la construction et l'analyse d'une base de données sur l'offre journalistique accessible en France via Facebook, Instagram, Twitter et YouTube. [Plus d'infos](http://gresec.univ-grenoble-alpes.fr/version-francaise/membres/emmanuel-marty-539633.kjsp). Contact :[emmanuel.marty@univ-grenoble-alpes.fr](emmanuel.marty@univ-grenoble-alpes.fr).
<hr>

**Jérôme Pacouret** (Sciences Po Grenoble / Pacte). Jérôme Pacouret est docteur de l'EHESS et postdoctorant dans le cadre du projet Feeding Bias. Il coordonne l'enquête par questionnaire sur les pratiques d'information et les usages des réseaux sociaux de la population française. [Plus d'infos sur ses recherches](https://cessp.cnrs.fr/-PACOURET-Jerome-). Contact : [pacouret.jerome@gmail.com](mailto:pacouret.jerome@gmail.com).

---

## **Actualités du projet**

<ul class="post-list">
        {% for post in site.categories.feedingbias offset: site.pagination + 1 %}
                <li><span class="date">{{ post.date | date: "%Y-%m-%d" }}</span> | <a class="link" href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
        {% endfor %}
</ul>
