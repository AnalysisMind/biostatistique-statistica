# EXERCICE D’APPLICATION 4: Comparaison de deux échantillons indépendants

En vue d’estimer les différences de productivité qui peuvent exister entre plusieurs types de forêts de hêtre de l’ardenne belge, Dagnélie (1957) a mesuré, en différents endroits la hauteur (qui est étroitement liée à la production en volume) des arbres les plus gros. Trois type de hêtraies ont été considérées au sein desquelles on a observé les hauteurs des arbres respectivement en 13 endroits, en 14 endroits et en 10 endroits différents, choisis au hasard et indépendamment les uns des autres. En chaque endroit, les cinq arbres les plus gros situés au sein d’une parcelle circulaire d’environ 15 m de rayon ont été mesurées, chacun deux fois, et pour chaque lieu, la moyenne des 10 observations a été calculée. Pour éviter la présentation de données trop nombreuse, seules ces moyennes ont été présentées dans le tableau ci-dessous :

| Type 1 | Type 2 | Type 3 |
|---|---|---|
| 23,4 | 22,5 | On voudrait savoir si la productivité est la même dans la forêt de type 2 et dans la forêt de type 3On voudrait savoir si la productivité est la même dans la forêt de type 2 et dans la forêt de type 318,9 |
| 24,4 | 22,9 | 21,1 |
| 24,6 | 23,7 | 21,2 |
| 24,9 | 24 | 22,1 |
| 25 | 24,4 | 22,5 |
| 26,2 | 24,5 | 23,6 |
| 26,3 | 25,3 | 24,5 |
| 26,8 | 26 | 24,6 |
| 27,6 | 26,2 | 26,2 |
| 26,8 | 26,4 | 26,7 |
| 26,9 | 26,7 |  |
| 27 | 26,9 |  |
| 27,7 | 27,4 |  |
|  | 28,5 |  |

## RESULTATS

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue (hauteurs des arbres) et une variable qualitative (type de forêt)

- On veut comparé deux échantillons indépendants

### Choix du test approprié

- Etude de la normalité de (type2 et type3)

Statistique - Statistiques élémentaires - Statistiques descriptives - Normalité - Cocher test de Shapiro-Wilk - Insérer dans variable ‘’type 2’’ et ‘’type 3’’ - Cliquer sur histogramme

P=0.9139>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.P=0.91151>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.P=0.9139>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.P=0.91151>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.

- Etude de l’homogénéité des variances

Statistique - Statistiques élémentaires - test t pour des échantillons indépendants par variables - Insérer dans variables ‘’type2’’ et ‘’type3’’ - Dans option cliquer sur ‘’Test de Levene’’ - Cliquer sur ‘’synthèse’’

| Test t pour des Echantillons Indépendants (Feuille de données2) Note : Variables traitées comme des échantillons indépendants |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|
|  | Moyenne Groupe 1 | Moyenne Groupe 2 | valeur t | dl | p | N Actifs Groupe 1 | N Actifs Groupe 2 | Ec-Type Groupe 1 | Ec-Type Groupe 2 |
| type2 vs. type3 | 25,38571 | 23,14000 | 2,617012 | 22 | 0,015740 | 14 | 10 | 1,773244 | 2,440947 |

| Test t pour des Echantillons Indépendants (Feuille de données2) Note : Variables traitées comme des échantillons indépendants |  |  |  |  |  |
|---|---|---|---|---|---|
|  | Ratio F Variances | P Variances | Levene | dl Levene | p Levene |
| type2 vs. type3 | 1,894870 | 0,285774 | 1,285309 | 22 | 0,269118 |

On a p variance= 0.28>α avec α=0,05 (méthode1); p Levene= 0.26>α avec α=0,05 (méthode2) donc les variances sont homogènes

Les distributions sont normales et leurs variances sont homogènes donc on peut utiliser un test paramétrique.

Test t pour échantillons indépendants par variables

Statistique - Statistiques élémentaires - test t pour des échantillons indépendants par variables - Insérer dans variables ‘’type2’’ et ‘’type3’’ - Cliquer sur ‘’synthèse: test t’’

| Test t pour des Echantillons Indépendants (Feuille de données2) Note : Variables traitées comme des échantillons indépendants |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|
|  | Moyenne Groupe 1 | Moyenne Groupe 2 | valeur t | dl | p | N Actifs Groupe 1 | N Actifs Groupe 2 | Ec-Type Groupe 1 | Ec-Type Groupe 2 |
| type2 vs. type3 | 25,38571 | 23,14000 | 2,617012 | 22 | 0,015740 | 14 | 10 | 1,773244 | 2,440947 |

| Test t pour des Echantillons Indépendants (Feuille de données2) Note : Variables traitées comme des échantillons indépendants |  |  |
|---|---|---|
|  | Ratio F Variances | P Variances |
| type2 vs. type3 | 1,894870 | 0,285774 |

t= 2.61, ddl= 22, p=0.015<α avec α=0,05, il y a donc une différence significative entre la productivité des forêts de type 2 et 3
