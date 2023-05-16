# HTML - CSS


## 1.Presentation et objectif de ses 5 jours

- Qui suis-je
- Qui êtes vous ?
- Quel est votre niveau informatique ?
- Ce que vous attendez de la formation

## 2.Presentation des outils et installation

- VS code : [Téléchargement](https://code.visualstudio.com/).
vs code est ce que l'on appelle un IDE ( intégrated developement environement )
c'est un outil de traitement de texte et de code qui nous facilite la création de site web,
application et bien d'autre.

- Inspecteur du navigateur
l'inspecteur est un outils présent dans tout les navigateur(Firefox, Opera,
 Edge, Chrome, ..)
C'est un outils indispensable pour les développeur web , il permet :
d'identifier des erreurs, des comportement voir même la vitesse/réactivité de notre page web

- Un dossier vide
Aussi simple que cela puisse paraitre tout les site internet
commencent dans un dossier vide, c'est ce que nous allons faire
avec notre première page html qui devrais ressembler a quelque chose comme ça :
[Premiere page web](http://info.cern.ch/hypertext/WWW/TheProject.html)

## 3. Un peu de théorie

- Le HTML ?
Le html est un langage dit de balisage (dit descriptif de donnée)
il nous permet de définir les diffèrent bloc de notre page web.

![Bloc html](./assets/Balise-de-base.png "Blocs html")

- La balise en detaille.

![Balise de plus pres](./assets/Balise-detaille.png "balise de plus pres")

- Et voici la structure indispensable a une page web.

![structure html de base](./assets/structure-fonctionnel.png "structure html de base")

## Exercice : 

- Inspectez la page d'accueil de Wikipedia d'un personnage publique et modifiez:

- La balise head et son contenu 
- La balise body et son contenu
- 3 balises quelconques pour lesquelles vous modifierez les attributs et contenu
- Pour finir modifiez une partie du css de ses derniers 

### Exemple css
Voici une page html sans css : 

![html sans css](./assets/html-no-css.png "html sans css")

Voici une page html avec css :

![html avec css](./assets/html-yes-css.png "html avec css")

![paragraphe rouge](./assets/p-css.png "paragraphe coloré avec du css")

## Exercice :

- Créez une page html

- Ajouter votre nom et prenom en titre principale 

- Ajoutez une photo miniature et un lien vers la photo initiale

- Ajoutez 3 sections avec un titre secondaire ( mon experience , mes compétences , ma formation ) [ chaque section contient un paragraphe ou une liste à puce]

- Ajoutez different titre , chacun ayant une taille differente 

[Example](codepen.io/Michamp/pen/LYQrPPv)



## 4.Containers , positionnement et comportement des elements .

### Liste des principales balises container : 

- div
- section
- article
- main
- header
- footer
- nav

Les containers servent à structurer votre code HTML

![Les conteneurs](./assets/bloc-et-conteneur.png "comparaison de conteneurs ambigu et clairs")

Chaque élément HTML est affiché en considérant le modèle suivant :

![bordure , marge internet/externe](./assets/mar-pad-bor.png "bordure , marge interne/externe")

### Propriété css fréquemment rencontrées : 

- Les propriétés width et height vont nous permettre de
définir la largeur et la hauteur de la boite « contenu »

- La propriété padding va nous permettre de définir la taille des marges internes
Important : le background ne s’applique QUE dans le padding !

- La propriété padding va nous permettre de définir la taille des marges internes
Important : le background ne s’applique QUE dans le padding!

- La propriété margin va nous permettre de définir la taille des marges externes.
Rem: la propriété margin varie entre deux éléments similaires

- display est une propriété très puissante puisqu’elle va nous permettre de modifier
la façon dont un élément va s’afficher dans la page : en ligne, sous forme de bloc, etc.
et donc la façon dont il va se comporter avec ses voisins:
inline : Les éléments de type inline vont venir essayer de se placer en ligne…,
block : Un élément de type block va toujours prendre toute la largeur disponible au sein de son
élément parent. Un élément de type block va toujours « aller à la ligne »
Un élément de type block peut contenir d’autres éléments de type block ou de type inline
Un élément de type inline ne peut pas contenir d’éléments de type block


### Les propriétés CSS liées aux différentes conteneurs

- Les propriétés width et height vont nous permettre de définir la largeur et la hauteur de la boite « contenu »

- La propriété padding va nous permettre de définir la taille des marges internes 
**remarque : le background ne s’applique QUE dans le padding!**

- La propriété border va nous permettre de définir des bordures pour notre élément 

- La propriété margin va nous permettre de définir la taille des marges externes.
**remarque : la propriété margin varie entre deux éléments similaires**

- La propriété box-sizing: border-box indique que l’on souhaite inclure les marges internes et les bordures dans le calcul de la taille d’un élément.

- La propriété display va nous permettre de définir un type d’affichage pour un élément

- display est une propriété très puissante puisqu’elle va nous permettre de modifier la façon dont un élément va s’afficher dans la page : en ligne, sous forme de bloc, etc. et donc la façon dont il va se comporter avec ses voisins

- Les éléments de type inline vont venir essayer de se placer en ligne , Un élément de type inline ne va occuper que la largeur nécessaire à l’affichage de son contenu par défaut.

- Un élément de type block va toujours prendre toute la largeur disponible au sein de son élément parent. Un élément de type block va toujours « aller à la ligne » , Un élément de type block peut contenir d’autres éléments de type block ou de type inline


### Pour resumer :

**propriété display**

- block :
        prend toute la largeur de l'ecran , retourne à la ligne 
        hauteur et largeur modifiable , peut contenir d'autre éléments block et inline
        ex: ```<div>,<p>```

- inline :
        espace minimum , se suivent l'un derrière l'autre
        hauteur et largeur mnon modifiables et ne peut contenir
        ex: ```<span>```

- inline-block :
        comme inline mais on peut modifier hauteur et largeur
        ex:```<img>```

- none :
        l'élément n'est pas du tout affiché ( ni même visible)

-flex et grid :
        pour mettre en place des layout ( que nous verrons plus tard )



## Exercice

- Realisez la maquette suivant en respectant les indication de box model indiquées ( certaines sont incomplètes )

![structure exercices](./assets/exo2.png "structure exercices")


### Liste des balises utilisées 

``` 
<html>      <head>      <body>
<meta>      <link>      <nav>
<p>         <a>         <q>
<header>    <footer>    <main>
<aside>     <section>   <article>
<span>      <div>
<table>     <th>    <tr>    <td>

``` 

### Liste des proprièté CSS 

```

display
color
background-color
margin
padding
border
width
height
box-sizing

```

Ref pour les differentes balises et proprieté css :
HTML
https://www.w3schools.com/tags/default.asp 
http://html5doctor.com/element-index/ 
https://developer.mozilla.org/fr/docs/Web/HTML 

CSS
https://www.w3schools.com/css/css_intro.asp
https://developer.mozilla.org/fr/docs/Web/CSS


Note: Mozilla MDN Web Docs peut être affiché en français

N’hésitez pas à Googler ou chercher directement sur Youtube des mots clés


## Sélecteurs CSS : introduction

- Sélectionner une balise

``` 
p {
	color:  red;
}
```
- Sélectionner une classe

```
.boite {
	display: inline-block;
}
```

- Sélectionner un id

``` 
#box-important {
	color: red;
}
```
- Sélectionner par référence à un parent
```
.box1 .box2 {
	color: red;
}
```

- Sélectionner un élément dans un autre

``` 
.box1 > .box2 {
	color: red;
}
```

- Pseudo sélecteur de survol d’un élément

``` 
p:hover{
    background-color:red;
}

```


## Exercices 

Repondre au question ecrit en commentaire dans le bloc CSS : [exercices](https://codepen.io/Michamp/pen/XWZBVxa)

### Réferences 

[Liste des sélecteurs:](https://www.w3schools.com/cssref/css_selectors.asp)

[Jeu sur les sélecteurs CSS :](https://flukeout.github.io/ )


## Positionner un élément

- La propriété position va nous permettre de de définir un type de positionnement
        La valeur static est la valeur par défaut de la propriété position. 
        Un élément HTML positionné avec position : static sera positionné selon le flux normal de la page.

- les propriétés top, left, bottom et right n’auront aucun effet sur les éléments positionnés avec position : static.

- Attribuer une position : relative à un élément va positionner l’élément dans le flux normal de la page tout comme position : static.
        position : relative va ensuite pouvoir être décalé par rapport à sa position initiale grâce aux propriétés top, left, bottom et right.

- Un élément positionné avec position: absolute va être positionné par rapport à son parent le plus proche positionné.
        Le point de référence pour les propriétés top, left, bottom et right va ainsi être le côté de l’élément parent.Un élément positionné avec position: absolute va ainsi pouvoir se placer par-dessus d’autres éléments.
        *La seule différence entre position: fixed et position: absolute est que l’élément ne va plus être positionné par rapport à son parent le plus proche mais par rapport au viewport, c’est-à-dire par rapport à la fenêtre visible*

**resumer**
propriété position

- static : propriété par défaut, ne change rien

- relative : comportement par défaut identique à static on peut modifier : top, left, right, bottom
        déplace l’élément “au dessus” des autres

- absolute : enlève l’élément de sa position normale le reste s’affiche comme si l’élément n’était pas là
        top, left, right, bottom sont relatifs au parent (html par défaut)

- fixed : colle l’élément au viewport ,on positionne avec top, left, right, bottom

- sticky : comportement par défaut identique à relative ,dès qu’on scrolle cela se transforme en fixed


[liste des positions avec un exemple :](https://codepen.io/Michamp/pen/PoQBQYY )

[Exemple pour sticky uniquement :](https://codepen.io/Michamp/pen/KKQBQwa )

### Exercices

![Exercices](./assets/exo3.png "Exercices a realisé")

[exemple à completer](https://codepen.io/Michamp/pen/JjpBpbe)
*Collez le code html , css dans les fichier respectif sur vscode pour vous simplifier la vie*

[correction](https://codepen.io/Michamp/pen/xxYJYRy)


