# Accueil

> Documentation des composants, pages et de l'API


## Fonctionnement des biens

---

#### Question

Savoir combien il y aura de biens récupérés depuis Immofacile

- Il y en a peu: on peut tous les récupérer dès le lancement du site et partout où il y a un tri ou des filtres, tout se fait sans rappeler l’API (beaucoup plus réactif mais on charge possiblement des biens que l’utilisateur ne verra jamais)
- Il y en a beaucoup: on fait un appel API à chaque fois que l’utilisateur change un filtre ou un tri (plus lent mais on ne charge que des données utiles)

#### Réponse

Environ 60 donc 1er cas

## Utilisation des icônes

---

#### Question

Quand on peut choisir l'icône en back (par exemple pour [/composants/liste-ville](les atouts d'un quartier)), il faudrait afficher la liste des icônes disponibles en back.  
Laisser la possibilité d'upload des SVGs peut être un problème suivant comment il est formatté

#### Réponse

...

## Personnalisation du site

---

#### Question

A quel point le site est personnalisable ?  

Est-ce qu'on peut par exemple décider sur la home d'enlever la section `Nos conseillers ont une réelle expertise de leur quartier`, ou de la placer après la section `Nos villes et quartiers` ?


#### Réponse

...

## Images et responsive

---

#### Question

Pour chaque image, on doit renvoyer une propriété `alt` qui est une description de l'image.  
Pour le responsive, il faut décider (suivant aussi ce qui est possible) si: 

- on définit pour chaque type les tailles d'image qu'il aura: par exemple, quand on upload l'image de header d'un bien, on génèrera 3 images de différentes largeur (300, 800, 1400) qui sont toutes renvoyées via l'API
- la génération d'image se fait quand on les appelle: on peut utiliser [Fly dynamic image resizer](https://fr.wordpress.org/plugins/fly-dynamic-image-resizer/)

#### Réponse

...

## WYSIWYG

---

#### Question

Comment on fontionne pour les sliders d'image au milieu des contenus ?
Le mieux serait d'avoir des blocs répétables => en back, on a un champ contenu qui peut contenir des blocs slider ou des blocs texte, autant qu'on veut

#### Réponse

...
