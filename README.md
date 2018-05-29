# Pokemon
## TP 1 :



1) Quel sont les problèmes engendrés par l’implémentation du code de chaque attaque dans la classe ?

Si plusieurs classes ont la même attaque, nous allons avoir une duplication inutile du même code/méthode dans chaque classe.

2) Quel sont les problèmes engendrés par cette solution ?

Il faut faire une classe pour chaque association possible. Ce qui est long, lourd, pas maintenable.

3) L’agrégation entre les classes Pokémon et Énergie a-t-elle une incidence ?

Oui, car si un pokémon est ko, l'énergie n’est pas détruite. Elle est conservé.

## TP 2 :



1) Quels sont les problèmes engendrés par cette solution ?

Il y a une redondance de la méthode “affiche()” se trouvant dans plusieurs classes, pas d'instanciation dynamique, trop de dépendances.

2) Quels sont les problèmes engendrés par cette solution ?

Il ne faut pas implémenter une nouvelle logique quand elle existe déjà.
