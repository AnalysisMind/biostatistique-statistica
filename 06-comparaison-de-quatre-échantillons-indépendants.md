# EXERCICE D’APPLICATION 6: Comparaison de quatre échantillons indépendants

Le tableau ci-dessous présente les mesures de rendements céréaliers effectuées pour quatre variétés différentes.

| Variété 1 | Variété 2 | Variété 3 | Variété 4 |
|---|---|---|---|
| 50 | 52 | 57 | 53 |
| 54 | 56 | 60 | 47 |
| 53 | 57 | 59 | 47 |
| 51 | 60 | 62 | 49 |
| 49 | 56 | 64 | 48 |
| 52 | 55 | 58 | 52 |
| 51 | 53 | 63 | 50 |
| 52 | 54 | 61 | 46 |

A partir d’une analyse judicieuse de ces données peut-on conclure que le rendement varie significativement selon la variété ?

## RESULTATS

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue (rendement) et une variable qualitative (variété), les quatre échantillons sont indépendants

- On veut comparé quatres échantillons indépendants

### Choix du test approprié

- Etude de la normalité

Statistique - Statistiques élémentaires - Statistiques descriptives - Normalité - Cocher test de Shapiro-Wilk - Insérer dans variable ‘’v1’’, ‘’v2’’, ‘’v3’’ et ‘’v4’’ - Cliquer sur histogramme

p=0.98>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.96>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.97>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.93>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.98>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.96>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.97>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.p=0.93>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.

- Etude de l’homogénéité

### Insérer ce tableau dans statistica

| rendement | Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Hypothèses - Cliquer sur ‘’Test de Levene (ANOVA)Test de Levene d'Homogénéité des Variances (Feuille de données4) Effet : variétés Degrés de liberté pour tous les F : 3, 28MCMCFprendement1,0312501,5446430,6676300,579004p=0.286>α avec α=0,05, les variances sont donc homogènesDe tout ce qui précède on peut donc faire un test paramétrique, notamment l’ANOVA de FisherStatistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’[N] résiduel’’ et ‘’Engrais’’ - Autres résultats - Hypothèses - Cliquer sur ‘’Test de Levene (ANOVA)Test de Levene d'Homogénéité des Variances (Feuille de données4) Effet : variétés Degrés de liberté pour tous les F : 3, 28MCMCFprendement1,0312501,5446430,6676300,579004p=0.286>α avec α=0,05, les variances sont donc homogènesDe tout ce qui précède on peut donc faire un test paramétrique, notamment l’ANOVA de Fishervariétés |
|---|---|
| 50 | V1 |
| 54 | V1 |
| 53 | V1 |
| 51 | V1 |
| 49 | V1 |
| 52 | V1 |
| 51 | V1 |
| 52 | V1 |
| 52 | V2 |
| 56 | V2 |
| 57 | V2 |
| 60 | V2 |
| 56 | V2 |
| 55 | V2 |
| 53 | V2 |
| 54 | V2 |
| 57 | V3 |
| 60 | V3 |
| 59 | V3 |
| 62 | V3 |
| 64 | V3 |
| 58 | V3 |
| 63 | V3 |
| 61 | V3 |
| 53 | V4 |
| 47 | V4 |
| 47 | V4 |
| 49 | V4 |
| 48 | V4 |
| 52 | V4 |
| 50 | V4 |
| 46 | V4 |

ANOVA

On utilise ANOVA (analyse of variance) car c’est le test idéal pour comparer plus de deux moyennes pour des échantillons indépendants

Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’variétes’’ et ‘’rendement’’ - Autres résultats - Hypothèses - Tout les effets/Graphiques et validé

p=0.000<α avec α=0,05Il y a donc une différence significative entre les rendements moyens des quatres variétésp=0.000<α avec α=0,05Il y a donc une différence significative entre les rendements moyens des quatres variétés

- Comparons donc les moyennes entre elles

Statistiques - ANOVA - Anova à un facteur - Validé - Dans variables mettre ‘’variétes’’ et ‘’rendement’’ - Autres résultats - Post hoc - HSD de Tukey

| Test HSD de Tukey ; variable rendement (Feuille de données4) Probabilités Approximatives des Tests Post Hoc Erreur : MC Inter = 5,2813, dl = 28,000 |  |  |  |  |  |
|---|---|---|---|---|---|
|  | variétés | {1} | {2} | {3} | {4} |
| 1 | V1 |  | 0,011203 | 0,000164 | 0,154893 |
| 2 | V2 | 0,011203 |  | 0,000792 | 0,000191 |
| 3 | V3 | 0,000164 | 0,000792 |  | 0,000164 |
| 4 | V4 | 0,154893 | 0,000191 | 0,000164 |  |

Variétes 2 et 3p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 2 et 4p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 3 et 4p=0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 2Variétes 2 et 3p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 2 et 4p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 3 et 4p=0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 2Variétes 1 et 2p=0.01<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 2Variétes 1 et 3p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 1 et 4p= 0.15>α avec α=0,05; il n’y a aucune différence significative entre les rendements des variétés 1 et 4Variétes 1 et 2p=0.01<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 2Variétes 1 et 3p= 0.000<α avec α=0,05; il y a une différence significative entre les rendements des variétés 1 et 3Variétes 1 et 4p= 0.15>α avec α=0,05; il n’y a aucune différence significative entre les rendements des variétés 1 et 4

On constate de manière générale qu’il y de différence significative entre les rendements moyens des différents variétés à l’exception des variétés 1 et 4 où les rendements moyens ne présentent aucune différence significative.
