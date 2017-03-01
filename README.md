**! Indentation** : Manière de structurer les choses pour nous permettre de clarifier son travail.

* nécessaire pour le travail à plusieurs

* Permet de se repérer plus facilement dans la hiérarchie



Head  / Métadonnées : informations en arrière plan.
Informations fonctionnelles de la page
Titre → `<title>`
Type de caractères →  `<meta charset=”utf-8”>`
Feuilles de styles →     `<link rel="stylesheet" href="/css/style.css">`
Frameworks → `<link>` / `<script>`

Body : Contenu visible du site
Header : Informations de fonctionnement relatives au site (menu, barre de recherche, Log in, logo ou nom du site)
Footer : Bas de page (coordonnées, navigation secondaire, etc…)

Div : Bloc d’éléments → permet de manipuler un ensemble d'éléments.

```html

<Section>
<Article>	 Ensemble d'éléments syntaxique permettant de manipuler un bloc.
<Div>

```
###### Ces 3 éléments représentent la même chose mais corresponde à des niveaux de représentation différents. section sera utilisé pour un grand ensemble, div pour un ensemble plus ou moin grand de type indéfinis et article pour un bloc contenant un article ( sous-titre, paragraphe. )

## Les commentaires :
	Les commentaires servent à noter des informations textuels au milieu du code sans perturber son exécution. Ils peuvent également servir à masquer une partie du code sans avoir à effacer son contenus.


+ commentaires en html : <!--  Zone de commentaire -->  →
+ commentaire en CSS : /*  Zone de commentaire   */
Déplacer un paragraphe d’un emplacement à un autre:
ctrl + flèche haut / bas.
Lexique :
Définitions générales Css :

### Class :
Éléments central du html / css, les classes permettent de sélectionner plusieurs éléments et de leur appliquer du style dans l’ensemble.
On définit à travers les classes, des propriétés communes à plusieurs éléments.
### Id :
	Identité de la balise, l’attribut ID permet d’identifier un balise précisément. Elle va nous permettre d’appliquer du style qui ne doit apparaître que sur cet élément.

  Terminologies Html / Css :

  <head> : Le head contient toutes les <meta> ou métadonnée. Ce sont les informations structurelles de la page qui n'apparaîtront pas directement à l'écran mais qui sont nécessaire pour le bon fonctionnement de la page.

  <body> : Représente le corps de la page HTML.(un seul par document)

  <header> : Partie haute de la page web/html. Contient en général le <h1> et la navigation <nav>

  	<link>  : balise servant à charger du contenus CSS -- police + feuille de style

  	<p> définit un paragraphe.
  <span> : pour sélectionner une partie du texte que l’on veut modifié.
  <strong> / <b> : affiche un texte en gras
  <u> : souligne un texte
  <i> : affiche le texte en italique
  <em> : italique ou gras pour un texte ( dépend du navigateur )
  <div> :définit une division ou une section,appelé aussi calque


  .container : la classe container va nous servir à définir un espace donné qui contient les données dans une partie de la page. C’est une classe que l’on définit soi même.

  attributs : les attributs sont les informations notées

  	float → left / right :
  Mettre une image en habillage du texte
  positionner un élément à droite ou à gauche d’un autre.
  inconvénients : sort du flux → certaines propriétés ne fonctionnent pas et les éléments ne sont plus relatif entre eux

  	font-family :change la police de caractères

### Typo / Font / Police de caractère :
	La police de caractère correspond à ce que l’on nomme en css la font-family.
Ce sont les visuels de caractère qui vont nous permettre de changer l’affichage du texte.
! ne pas oublier d’enregistrer et de recharger la page pour avoir un visuel de son code!*
