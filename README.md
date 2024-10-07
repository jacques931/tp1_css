
# Devoir Maison CSS 1

Les structures du projet reposent sur la grille Bootstrap pour un alignement fluide. J'ai limité la création de nouvelles classes pour maximiser l'utilisation des composants existants. La plupart des couleurs ne sont pas à l’identique par rapport aux images.

**Url :** [https://jacques931.github.io/tp1_css/](https://jacques931.github.io/tp1_css/)

## Header :
Le header a été conçu entièrement en CSS sans utiliser de composants Bootstrap, car il n'a pas nécessité de modifications complexes. J'ai opté pour un flexbox avec `justify-content: space-between` afin de séparer les éléments d'un côté à l'autre du header, à savoir le logo à gauche et la barre de recherche à droite.

## Navbar :
Initialement, la barre de navigation (navbar) a été conçue uniquement avec du CSS, en utilisant des flexbox pour l'alignement horizontal des liens et la gestion du sous-menu. Cependant, pour assurer un alignement parfait entre la barre de navigation, la section principale et les autres éléments de la page, j'ai intégré le système de grille Bootstrap pour le positionnement.

La gestion du sous-menu reste entièrement gérée par des flexbox et des positions CSS, permettant ainsi une meilleure maîtrise du comportement des sous-éléments lors du survol. Bootstrap a été utilisé uniquement pour les aspects structurels, garantissant une flexibilité maximale.

## Section principale :
La section principale du tableau de bord utilise un mélange de Bootstrap et de CSS personnalisé. La grille de Bootstrap est employée pour définir la structure en colonnes, tandis que le style des éléments individuels, tels que les cartes de contenu ou les titres, est géré par des règles CSS personnalisées.

## Footer :
Le footer repose principalement sur Bootstrap, en utilisant la grille pour organiser les éléments en colonnes de manière égale. Chaque élément de la liste prend une largeur équivalente, sauf pour l'image, qui est plus petite et positionnée de manière serrée à droite. La couleur du footer a été modifiée en CSS pour se rapprocher visuellement de l'image.

## Mobile :
Pour la version mobile, une largeur de 767px a été définie, ce qui modifie la direction du flex de la barre de navigation. Une bordure est ajoutée en bas des éléments du menu et en haut du premier. La marge supérieure de la barre de navigation est supprimée, l’image ainsi que la barre de recherche s'étendent sur toute la largeur, et la hauteur des éléments du menu est ajustée, avec suppression de celui à droite. Un `z-index` est appliqué pour gérer l'affichage du sous-menu, bien qu'il ne soit pas visible sur l’image en mobile, donc aucune modification n'a été apportée à son comportement. Seules l'en-tête et la barre de navigation étant visibles sur l’image en mobile, les autres ajustements d'espacement ou modifications n'ont pas été effectués pour le reste de la structure.
