---
title: Documentation
---

## Prose.io

- [http://prose.io/#AMVR/amvr.github.io/](http://prose.io/#AMVR/amvr.github.io/)
- Se connecter grâce au compte Github
- Menu en haut à gauche > Language > choisir French (puis Menu > Prose)

## Structure des dossiers et fichiers

- Le dossier "pages" contient les pages du site et les sous-dossiers des pages Activités et Mécénat
- Le dossier "brouillons" contient les pages en cours de rédaction
- Le dossier "fichiers" contient les fichiers PDF, images, etc...
- Le dossier "\_includes" contient les menus haut et bas du site (de simples listes de liens)
- Le fichier "index.md", c'est le contenu de la page d'accueil du site

## Actions sur les dossiers et fichiers

- Cliquer sur un dossier pour afficher son contenu
- Modifier un fichier en cliquant sur son nom ou sur le lien "modifier" à sa droite
- Supprimer un fichier en cliquant sur l'iĉone Corbeille à droite
- La recherche se fait sur les noms des dossiers et des fichiers (attention aux accents)

## Brouillons

Les pages de brouillons sont créées dans le dossier "brouillons".

Une fois rédigée et prête pour relecture, cette page peut-être partagée en donnant son adresse (URL) ; quelque chose comme :  
http://amis-musees-rouen.fr/brouillons/brouillon-activites-decembre.html

L'adresse (URL) se décompose ainsi :

- Le nom de domaine du site : http://amis-musees-rouen.fr
- Le dossier "brouillons" : /brouillons
- La page : /brouillon-activites-decembre.html

**À noter : les fichiers que nous modifions se terminent par _.md_ mais les adresses des pages se terminent par _.html_**

Lorsque le brouillon est relu, corrigé et prêt à être diffusé, il suffit de copier/coller son contenu dans le dossier "pages", dans le fichier _.md_ qui correspond.

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

Ainsi, lors de la création d'une page au sein de Prose.io, le champ nom de fichier doit comporter quelque chose comme "pages/la-nouvelle-page.md".

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

<pre>
---
title: Titre de la page
---
</pre>

Avec :

- trois tirets du 6
- title: suivi du titre de la page
- trois tirets du 6

## Titre de niveau 2

<pre>
## Titre de niveau 2
</pre>

Le titre de niveau 2 est précédé de deux croisillons.

### Titre de niveau 3

<pre>
### Titre de niveau 3
</pre>

Le titre de niveau 3 est précédé de trois croisillons.

**/!\ Nous n'utilisons pas de titres de niveau 1 au sein des pages.**

## Paragraphes

Un paragraphe est simplement une ou plusieurs lignes consécutives de texte, séparées par une ou plusieurs lignes vides.

Pour un saut de ligne simple, terminer la ligne par deux espaces puis taper «Entrée».  
Comme ici.  
Ou encore là.

## Liens

Les liens s'écrivent ainsi : [Texte affiché](http://example.com).

<pre>
Les liens s'écrivent ainsi : [Texte affiché](http://example.com).
</pre>

Avec :

- le texte affiché entre crochets
- l'adresse de la page (URL) entre parenthèses

Lien vers une page interne au site : [Mécénat](http://amis-musees-rouen.fr/pages/mecenat.html).

<pre>
[Mécénat](http://amis-musees-rouen.fr/pages/mecenat.html).
</pre>

## Images

![Logo AMVR blanc](/fichiers/logo-amvr-bleu.png)

L'insertion d'image s'écrit ainsi :

<pre>
![Logo AMVR blanc](/fichiers/logo-amvr-bleu.png)
</pre>

Avec :

- Point d'exclamation
- Court texte descriptif de l'image entre crochets
- Chemin vers le fichier image : ici le fichier "logo-amvr-bleu.png" est situé dans le dossier "fichiers" (ne pas oublier les barres obliques)

### Taille des images

Les images doivent être redimensionnées avant d'être envoyées.

La largeur idéale (maximum) est de 600 pixels.  
La hauteur importe peu.

## Gras et italique

Voici du _texte en italique_, **texte en gras** et **_en gras et italique_**.

<pre>
Voici du _texte en italique_, **texte en gras** et **_en gras et italique_**.
</pre>

Deux astérisques encadrent le texte pour le gras et un tiret du 8 (underscore) pour l'italique.

## Bloc de citation

> Un bloc de citation est précédé d'un chevron.
> Sur chaque ligne.
>
> Et peut contenir plusieurs paragraphes.
>
> En utilisant des lignes vides.
>
> Les blocs de citation peuvent contenir du *texte en italique*, 
> du **texte en gras**, 
> des [liens](http://example.com), etc...

<pre>
> Un bloc de citation est précédé d'un chevron.
> Sur chaque ligne.
>
> Et peut contenir plusieurs paragraphes.
>
> En utilisant des lignes vides.
>
> Les blocs de citation peuvent contenir du *texte en italique*, 
> du **texte en gras**, 
> des [liens](http://example.com), etc...
</pre>

**/!\ À ce jour, novembre 2015, l'aperçu des blocs de citation ne fonctionne pas avec prose.io.**

## Listes

Les listes sont précédées d'un saut de ligne.

### Liste à puces

- pour une liste à puces
- chaque ligne est précédée
- d'un tiret du 6

<pre>
- pour une liste à puces
- chaque ligne est précédée
- d'un tiret du 6
</pre>

### Liste numérotée

1. pour une liste numérotée
2. chaque ligne est précédée
3. de son numéro et d'un point


<pre>
1. pour une liste numérotée
2. chaque ligne est précédée
3. de son numéro et d'un point
</pre>