# Maison de famille

> Documentation des composants, pages et de l'API


## Questions en attente

---

#### Fonctionnement des biens

Savoir combien il y aura de biens récupérés depuis Immofacile

- Il y en a peu: on peut tous les récupérer dès le lancement du site et partout où il y a un tri ou des filtres, tout se fait sans rappeler l’API (beaucoup plus réactif mais on charge possiblement des biens que l’utilisateur ne verra jamais)
- Il y en a beaucoup: on fait un appel API à chaque fois que l’utilisateur change un filtre ou un tri (plus lent mais on ne charge que des données utiles)


#### Utilisation des icônes

Quand on peut choisir l'icône en back (par exemple pour [/composants/liste-ville](les atouts d'un quartier)), il faudrait afficher la liste des icônes disponibles en back.  
Laisser la possibilité d'upload des SVGs peut être un problème suivant comment il est formatté


#### Personnalisation du site

A quel point le site est personnalisable ?  

Est-ce qu'on peut par exemple décider sur la home d'enlever la section `Nos conseillers ont une réelle expertise de leur quartier`, ou de la placer après la section `Nos villes et quartiers` ?
