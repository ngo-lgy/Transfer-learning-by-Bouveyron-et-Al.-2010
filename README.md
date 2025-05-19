# Transfert-learning-by-Bouveyron-et-Al.-2010

Le présent projet ne peut être considéré comme indépendant du projet intitulé " Améliorer la régression linéaire multiple grâce au transfert d'apprentissage ", dont la lecture est nécessaire avant d’aborder celui-ci.
L’objectif ici est de montrer comment, dans l’étude citée, il est possible d’estimer une transformation entre les fonctions de régression des populations source et cible.
L’exemple choisi est celui d’une agence immobilière située sur la côte Est des États-Unis, qui dispose d’un modèle de régression du prix des logements en fonction de plusieurs variables descriptives du logement, estimé à partir d’un large échantillon d’apprentissage.
Cette entreprise souhaite désormais s’implanter sur la côte Ouest, en y ouvrant plusieurs agences. Pour cela, elle envisage de réutiliser son modèle de régression existant sans investir excessivement en temps ou en ressources dans la collecte de nouvelles données sur le marché immobilier local.
Bien qu’elle admette que la relation entre les variables descriptives et les prix immobiliers puisse différer d’une côte à l’autre, elle estime que ces écarts restent relativement limités.

Nous expliquerons donc comment il est possible, dans ce contexte, d’élaborer un modèle de transformation entre les modèles de régression des côtes Est et Ouest, une démarche qui pourrait s’étendre à bien d’autres situations.
Un estimateur sera ainsi construit en transférant les connaissances de la population de la côte Est (appelée population source ou de référence) vers celle de la côte Ouest (appelée population cible), en estimant la transformation entre leurs fonctions de régression respectives.
