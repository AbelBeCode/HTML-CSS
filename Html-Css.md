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

![Bloc html](./Balise-de-base.png "Blocs html")

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

### Pour resumer :

** propriété display **

- block :
        prend toute la largeur de l'ecran , retourne à la ligne 
        hauteur et largeur modifiable , peut contenir d'autre éléments block et inline
        ex: <div>,<p>

- inline :
        espace minimum , se suivent l'un derrière l'autre
        hauteur et largeur mnon modifiables et ne peut contenir
        ex: <span>

- inline-block :
        comme inline mais on peut modifier hauteur et largeur
        ex: <img>

- none :
        l'élément n'est pas du tout affiché ( ni même visible)

-flex et grid :
        pour mettre en place des layout ( que nous verrons plus tard )


## Exercice

- Realisez la maquette suivant en respectant les indication de box model indiquées ( certaines sont incomplètes )

![structure exercices](./assets/exo2.png "structure exercices")

