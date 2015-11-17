---
title: Documentation
---

## Prose.io

- [http://prose.io/#AMVR/amvr.github.io/](http://prose.io/#AMVR/amvr.github.io/)
- Se connecter grâce au compte Github
- Menu en haut à gauche > Language > choisir French (puis Menu > Prose)

## Structure des dossiers et fichiers

- Le dossier "pages" contient les pages du site et les sous-dossiers des pages Activités et Mécénat
- Le dossier "fichiers" contient les fichiers PDF, images, etc...
- Le dossier "\_includes" contient les menus haut et bas du site (de simples listes de liens)
- Le fichier "index.md", c'est le contenu de la page d'accueil du site

## Actions sur les dossiers et fichiers

- Cliquer sur un dossier pour afficher son contenu
- Modifier un fichier en cliquant sur son nom ou sur le lien "modifier" à sa droite
- Supprimer un fichier en cliquant sur l'iĉone Corbeille à droite
- La recherche se fait sur les noms des dossiers et des fichiers (attention aux accents)

## Créer une nouvelle page

Les pages doivent être placées dans le dossier "pages".

Le nommage des fichiers doit respecter ces règles : 

- Pas d'accent
- Pas d'espace
- Pas de majuscule

Uniquement :

- des lettres minuscules
- des chiffres
- des tirets (du 6 ou du 8)

L'extension de fichier est ".md" pour [Markdown](https://fr.wikipedia.org/wiki/Markdown).

Ainsi, lors de la création d'une page au sein de Prose.io, le champ nom de fichier doit comporter quelque chose comme "/pages/la-nouvelle-page.md".

## Actions lors de l'écriture

Icône à droite :

- Crayon : écrire
- Œil : voir un aperçu
- Roue crantée : supprimer le fichier
- Disquette : enregistrer les modifications

Enregistrement :

- Les modifications du texte sont visibles
- Un message est demandé. Il est assez libre et peut être quelque chose comme "correction d'une coquille", "ajout des activités de janvier", etc...

## Titre de la page

Tous les fichiers commencent par les 3 lignes :

- trois tirets du 6
- title: suivi du titre de la page
- trois tirets du 6

## Titre de niveau 2 : deux croisillons

### Titre de niveau 3 : trois croisillons

/!\ Nous n'utilisons pas de titres de niveau 1 au sein des pages.

## Paragraphes

Un paragraphe est simplement une ou plusieurs lignes consécutives de texte, séparées par une ou plusieurs lignes vides.

Pour un saut de ligne simple, terminer la ligne par deux espaces puis taper «Entrée».  
Comme ici.  
Ou encore là.

## Liens

### Lien externe

Les liens s'écrivent de la manière suivante : [Texte affiché](http://example.com), avec :

- le texte affiché entre crochets
- l'adresse URL entre parenthèses

### Lien interne

Les liens peuvent pointer vers des pages externes comme dans l'exemple précédent.

Mais aussi vers des pages internes : [Mécénat](/pages/mecenat.html).

Le chemin interne au site se décompose ainsi :

- /pages : Dossier "pages", précédé d'un slash
- /mecenat.html : Fichier "mecenat.md" où ".md" est remplacé par ".html"

## Images

L'insertion d'image s'écrit ainsi :

![Logo AMVR blanc](/fichiers/logo-amvr-bleu.png)

- Point d'exclamation
- Court texte descriptif de l'image entre crochets
- Chemin vers le fichier image : ici le fichier "logo-amvr-bleu.png" est situé dans le dossier "fichiers"

![2000-callow.jpg]({{site.baseurl}}/fichiers/oeuvres/2000-callow.jpg)

## Gras et italique

Les paragraphes peuvent contenir du *texte en italique* et du **texte en gras** en encadrant le texte avec une ou deux étoiles. Avec trois étoiles, le ***texte est en gras et en italique***.

## Bloc de citation

> Un bloc de citation est précédé d'un chevron.
> Sur chaque ligne.
>
> Et peut contenir plusieurs paragraphes.
>
> En utilisant des lignes vides.
>
> Les blocs de citation peuvent contenir du *texte en italique*, du **texte en gras**, des [liens](http://example.com), etc...

/!\ À ce jour, novembre 2015, l'aperçu des blocs de citation ne fonctionne pas avec prose.io.

## Listes

Les listes sont précédées d'un saut de ligne.

### Liste à puces

- pour une liste à puces
- chaque ligne est précédée
- d'un tiret du 6

### Liste numérotée

1. pour une liste numérotée
2. chaque ligne est précédée
3. de son numéro et d'un point
