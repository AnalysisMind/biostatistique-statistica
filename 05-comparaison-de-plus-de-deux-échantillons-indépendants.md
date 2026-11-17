# EXERCICE D’APPLICATION 5: Comparaison de plus de deux échantillons indépendants

Pour évaluer l'impact sur l'environnement de 3 types d’engrais, on considère 3 parcelles identiques sur lesquelles on cultive la même variété de céréale, mais avec 3 types d'engrais. La variabilité mesurée par voie chimique sur des échantillons ramenés en laboratoire est la concentration résiduelle en azote dans le sol, exprimée en kg N/ha. Sur chacune des parcelles, l’on prélève 5 échantillons, à la même profondeur et dans des conditions identiques. Les résultats obtenus sont présentés dans le tableau ci-dessous:

| Echantillons | Parcelle1 | Parcelle2 | Il y a-t-il une différence significative entre les 3 types d’engrais ?Il y a-t-il une différence significative entre les 3 types d’engrais ?Parcelle3 |
|---|---|---|---|
| №1 | 47 | 55 | 54 |
| №2 | 53 | 54 | 50 |
| №3 | 49 | 58 | 51 |
| №4 | 50 | 61 | 51 |
| №5 | 46 | 52 | 49 |

## RESULTATS

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue (Azote) et une variable qualitative (Parcelle), les trois échantillons sont indépendants

- On veut comparé trois échantillons indépendants

### Choix du test approprié

- Etude de la normalité

Statistique - Statistiques élémentaires - Statistiques descriptives - Normalité - Cocher test de Shapiro-Wilk - Insérer dans variable ‘’parcelle1’’, ‘’parcelle2’’ et ‘’parcelle2’’ - Cliquer sur histogramme

p=0.83265>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.84411>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.45316>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.83265>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.84411>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.45316>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.

- Etude de l’homogénéité

### Insérer ce tableau dans statistica

| [N] résiduel | Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Hypothèses - Cliquer sur ‘’Test de Levene (ANOVA)Test de Levene d'Homogénéité des Variances (Feuille de données5) Effet : Engrais Degrés de liberté pour tous les F : 2, 12MCMCFp[N] résiduel3,2000002,3000001,3913040,286142p=0.286>α avec α=0,05, les variances sont donc homogènesStatistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Hypothèses - Cliquer sur ‘’Test de Levene (ANOVA)Test de Levene d'Homogénéité des Variances (Feuille de données5) Effet : Engrais Degrés de liberté pour tous les F : 2, 12MCMCFp[N] résiduel3,2000002,3000001,3913040,286142p=0.286>α avec α=0,05, les variances sont donc homogènesEngrais |
|---|---|
| 47 | E1 |
| 53 | E1 |
| 49 | E1 |
| 50 | E1 |
| 46 | E1 |
| 55 | E2 |
| 54 | E2 |
| 58 | E2 |
| 61 | E2 |
| 52 | E2 |
| 54 | E3 |
| 50 | E3 |
| 51 | E3 |
| 51 | E3 |
| 49 | E3 |

ANOVA

On utilise ANOVA (analyse of variance) car c’est le test idéal pour comparer plus de deux moyennes pour des échantillons indépendants

Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Hypothèses - Tout les effets/Graphiques et validé

p=0.005<α avec α=0,05Il y a donc une différence significative entre les trois types d’engraisp=0.005<α avec α=0,05Il y a donc une différence significative entre les trois types d’engrais

- Comparons donc les moyennes entre elles

Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Post hoc - HSD de Tukey

| Test HSD de Tukey ; variable [N] résiduel (Feuille de données5) Probabilités Approximatives des Tests Post Hoc Erreur : MC Inter = 7,8333, dl = 12,000 |  |  |  |  |
|---|---|---|---|---|
|  | Engrais | {1} | {2} | {3} |
| 1 | E1 |  | 0,005164 | 0,515003 |
| 2 | E2 | 0,005164 |  | 0,038019 |
| 3 | E3 | 0,515003 | 0,038019 |  |

Engrais 1 et 2

p=0.005<α avec α=0,05; il y a une différence significative entre les résultats des engrais 1 et 2

Engrais 1 et 3

p= 0.515>α avec α=0,05; il n’y a aucune différence significative entre les résultats des engrais 1 et 3

Engrais 2 et 3

p=0.038<α avec α=0,05; il y a une différence significative entre les résultats des engrais 2 et 3

Il y a une différence significative entre les résultats des différents engrais utilisé à l’exception des engrais 1 et 3 où il n’y a aucune différence significative.
