# EXERCICE D’APPLICATION 3: Comparaison de deux échantillons appariés

Pour comparer la longueur des sépales et des pétales chez l’espèce d’iris appelée Setosa, 30 individus ont été considérés. Les résultats obtenus sont présentés dans le tableau ci-dessous:

| individu | Longueur Sépales | Longueur Pétales |
|---|---|---|
| 1 | 5,1 | 1,4 |
| 2 | 4,9 | 1,4 |
| 3 | 4,7 | 1,3 |
| 4 | 4,6 | 1,5 |
| 5 | 5 | 1,4 |
| 6 | 5,4 | 1,7 |
| 7 | 4,6 | 1,4 |
| 8 | 5 | 1,5 |
| 9 | 4,4 | 1,4 |
| 10 | 4,9 | 1,5 |
| 11 | 5,4 | 1,5 |
| 12 | 4,8 | 1,6 |
| 13 | 4,8 | 1,4 |
| 14 | 4,3 | 1,1 |
| 15 | 5,8 | 1,2 |
| 16 | 5,7 | 1,5 |
| 17 | 5,4 | 1,3 |
| 18 | 5,1 | 1,4 |
| 19 | 5,7 | 1,7 |
| 20 | 5,1 | 1,5 |
| 21 | 5,4 | 1,7 |
| 22 | 5,1 | 1,5 |
| 23 | 4,6 | 1 |
| 24 | 5,1 | 1,7 |
| 25 | 4,8 | 1,9 |
| 26 | 5 | 1,6 |
| 27 | 5 | 1,6 |
| 28 | 5,2 | 1,5 |
| 29 | 5,2 | 1,4 |
| 30 | 4,7 | 1,6 |

Il y a-t-il une différence significative entre les longueurs de ces parties de la fleur?

## RESULTATS

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue et d’une variable qualitative (partie de la fleur)

- On veut comparé deux échantillons appariés (deux mesures sur un même individu)

### Choix du test approprié

- Etude de la normalité

Calculons di

Dans statistica on clique sur la colonne où l’on veut mettre ‘’di’’, dans la case ‘’Description détaillée’’ en bas de la boîte de dialogue inséré ‘’=sépales-pétales’’. On a

| sépales | pétales | On étudie la normalité avec le test de Shapiro-wilkStatistique - Statistiques élémentaires - Statistiques descriptives - Normalité - Cocher test de Shapiro-Wilk - Insérer dans variable ‘’di’’ - Cliquer sur histogrammeP=0.300663>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.On peut donc faire un test paramétrique; ce sera dans ce cas un test t de student des échantillons appariés.On étudie la normalité avec le test de Shapiro-wilkStatistique - Statistiques élémentaires - Statistiques descriptives - Normalité - Cocher test de Shapiro-Wilk - Insérer dans variable ‘’di’’ - Cliquer sur histogrammeP=0.300663>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.On peut donc faire un test paramétrique; ce sera dans ce cas un test t de student des échantillons appariés.di |
|---|---|---|
| 5,1 | 1,4 | 3,7 |
| 4,9 | 1,4 | 3,5 |
| 4,7 | 1,3 | 3,4 |
| 4,6 | 1,5 | 3,1 |
| 5 | 1,4 | 3,6 |
| 5,4 | 1,7 | 3,7 |
| 4,6 | 1,4 | 3,2 |
| 5 | 1,5 | 3,5 |
| 4,4 | 1,4 | 3 |
| 4,9 | 1,5 | 3,4 |
| 5,4 | 1,5 | 3,9 |
| 4,8 | 1,6 | 3,2 |
| 4,8 | 1,4 | 3,4 |
| 4,3 | 1,1 | 3,2 |
| 5,8 | 1,2 | 4,6 |
| 5,7 | 1,5 | 4,2 |
| 5,4 | 1,3 | 4,1 |
| 5,1 | 1,4 | 3,7 |
| 5,7 | 1,7 | 4 |
| 5,1 | 1,5 | 3,6 |
| 5,4 | 1,7 | 3,7 |
| 5,1 | 1,5 | 3,6 |
| 4,6 | 1 | 3,6 |
| 5,1 | 1,7 | 3,4 |
| 4,8 | 1,9 | 2,9 |
| 5 | 1,6 | 3,4 |
| 5 | 1,6 | 3,4 |
| 5,2 | 1,5 | 3,7 |
| 5,2 | 1,4 | 3,8 |
| 4,7 | 1,6 | 3,1 |

- Test t de student des échantillons appariés

Statistique - Statistiques élémentaires - test t pour des échantillons appariés - Insérer dans variables ‘’sépales’’ et ‘’pétales’’ - Cliquer sur ‘’synthèse: Test t’’

| Test t pour des Echantillons Appariés (Statistica2) Différences significatives marquées à p < ,05000 |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|
|  | Moyenne | Ec-Type | N | Différ. | Ec-Type | t | dl | p |
| sépales | 5,026667 | 0,372256 |  |  |  |  |  |  |
| pétales | 1,473333 | 0,185571 | 30 | 3,553333 | 0,370213 | 52,57088 | 29 | 0,000000 |

t=52,57; dl=29; p=0,00000<α avec α=0.05, de plus tcalculé= 52,57 > tcritique(ddl=29,α=0.05)= 2.0452

Donc il y a une différence significative entre la longueur des sépales et celle des pétales.
