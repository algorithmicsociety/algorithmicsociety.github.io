---

layout:     default
title:      Bienvenue
type:       page
navigation: false
details:    true

date:       2019-10-14
image:      header-1.jpg
excerpt:    "La chaire Société algorithmique est une des chaires de recherche de l'institut <b>MIAI</b> (Multidisciplinary Institute in Artificial Intelligence) de l'Université Grenoble Alpes"
gradient:   2

---

La chaire Société algorithmique conduit des recherches sur le tournant algorithmique de la société contemporaine. Elle étudie l'intelligence artificielle dans ses contextes sociaux, soutient la recherche multidisciplinaire sur les biais de l'intelligence artificielle et favorise le développement d'une litératie algorithmique parmi les étudiants en sciences sociales.

<hr>

[Les projets](https://algorithmicsociety.github.io/projets.html) • [Les participant•es](https://algorithmicsociety.github.io/participants.html) • [Le séminaire](https://algorithmicsociety.github.io/seminaire.html) • [Les publications](https://algorithmicsociety.github.io/publications.html)

<hr>

<h2>Actualité de la chaire</h2>
<p>Voir la rubrique « Actualités » pour retrouver l'ensemble des actualités de la chaire postées sur ce site.</p>

<ul class="post-list">
{% for post in site.posts limit:site.pagination %}
      <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}
      </span> |
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
          {{ post.title }}
        </a>
      <br>
{% endfor %}
</ul>
