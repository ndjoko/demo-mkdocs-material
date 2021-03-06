# 2. Générateur de site statique

Le générateur de site statique est une pile logicielle, c'est l'application à livrer ou à déployer en continu. Dans ce document, on propose un solution simple et performante de site documentaire avec MkDocs et le thème Google Material.

**Pratique**: En savoir plus sur [MkDocs](http://www.mkdocs.org/) et [Material for MkDocs](http://squidfunk.github.io/mkdocs-material/), explorer [static site generator](https://www.staticgen.com/).

## Qu'est-ce qu'un générateur de site statique ?

!!! question "Qu'est-ce qu'un générateur de site statique ?"
    Le concept de base d'un générateur de site statique (aussi appelé moteur de site statique) est simple: {==prendre du contenu et des données dynamiques et générer des fichiers HTML/JavaScript/CSS statiques pouvant être déployés sur le serveur.==} Cette idée n'est pas nouvelle. [^static-site-generators]

[^static-site-generators]: [Voir cet excellent source  du blog O'Reilly](https://www.oreilly.com/ideas/static-site-generators).

On peut caractériser les sites fabriqués de cette manière :

* Il existe de nombreux services, gratuits et payants, qui offrent la possibilité d'ajouter des aspects dynamiques dans des pages statiques.
* Les fichiers de sites statiques sont livrés à l'utilisateur final exactement comme ils le sont sur le serveur.
* Il n'y a pas de langage côté serveur.
* Il n'y a pas de base de données.
* Les sites statiques sont en HTML, CSS et JavaScript.
* Les performances, l'hébergement, la sécurité, la gestion des versions de contenu sont des avantages des sites statiques.

## Le projet Mkdocs

[MkDocs](http://www.mkdocs.org/) est un générateur de site statique rapide et simple visant à créer des projets de documentation/à documenter des projets. Les fichiers sources de documentation sont écrits en langage Markdown et il est configuré à partir d'un seul fichier de configuration (décrit en YAML).

## Material for MkDocs

Material est un thème pour MkDocs. Il est construit en utilisant [les directives de Google Material Design](https://material.io/guidelines/material-design/).

![](http://squidfunk.github.io/mkdocs-material/images/material.png)

## L'annuaire Staticgen

N'hésitez pas à explorer [static site generator](https://www.staticgen.com/) qui recense les nombreux projets de générateurs de site statique.
