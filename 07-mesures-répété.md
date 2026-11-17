# EXERCICE D’APPLICATION 7: Mesures répété

| Dose | J0 | J3 | J6 | J9 | J12 | J15 | J18 |
|---|---|---|---|---|---|---|---|
| d0 | 0,003 | 0,002 | 0,002 | 0,003 | 0,001 | 0,029 | 0,023 |
| d0 | 0,001 | 0,001 | 0,004 | 0,003 | 0,002 | 0,008 | 0,003 |
| d0 | 0,009 | 0,006 | 0,002 | 0,002 | 0,001 | 0,013 | 0,003 |
| d300 | 0,029 | 0,014 | 0,01 | 0,008 | 0,022 | 0,003 | 0,002 |
| d300 | 0,006 | 0,02 | 0,003 | 0,018 | 0,003 | 0,02 | 0,006 |
| d300 | 0,016 | 0,001 | 0,007 | 0,006 | 0,014 | 0,007 | 0,007 |
| d600 | 0,029 | 0,008 | 0,013 | 0,02 | 0,002 | 0,024 | 0,05 |
| d600 | 0,005 | 0,024 | 0,002 | 0,003 | 0,008 | 0,022 | 0,002 |
| d600 | 0,006 | 0,001 | 0,001 | 0,002 | 0,008 | 0,01 | 0,013 |
| d900 | 0,014 | 0,01 | 0,004 | 0,01 | 0,002 | 0,035 | 0,057 |
| d900 | 0,009 | 0,004 | 0,004 | 0,016 | 0,003 | 0,027 | 0,009 |
| d900 | 0,017 | 0,017 | 0,003 | 0,011 | 0,035 | 0,049 | 0,009 |
| d1200 | 0,019 | 0,001 | 0,021 | 0,011 | 0,02 | 0,043 | 0,021 |
| d1200 | 0,004 | 0,027 | 0,038 | 0,017 | 0,007 | 0,002 | 0,041 |
| d1200 | 0,07 | 0,023 | 0,005 | 0,01 | 0,023 | 0,021 | 0,044 |
| d1500 | 0,026 | 0,035 | 0,009 | 0,002 | 0,014 | 0,017 | 0,026 |
| d1500 | 0,02 | 0,02 | 0,014 | 0,008 | 0,001 | 0,002 | 0,024 |
| d1500 | 0,084 | 0,024 | 0,049 | 0,003 | 0,007 | 0,015 | 0,03 |

Pour déterminer la dose optimale de déjections pour une bonne production d’algue, on a testé 6 différentes doses en triplicatas. Tous les 3 jours pendant 18 jours, la [chlo a] a été mesurée sur chaque unité d’observation.

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue [chlo a], deux variables qualitatives (temps et dose)

- On est en présence de mesures répété

- On doit répondre au trois questions suivantes

Es ce que la [chlo a] varie selon la dose ?

Es ce que la [chlo a] varie selon le temps ?

Il y a t’il une interaction entre la dose et temps ?

### Choix du test appropié

### Etudions la sphéricité

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’) - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Sphéricité

| Test de Sphéricité de Mauchley (Feuille de données32) Paramétrisation sigma-restreinte Décomposition efficace de l'hypothèse |  |  |  |  |
|---|---|---|---|---|
|  | W | Chi-Deux | dl | p |
| TEMPS | 0,111886 | 21,41601 | 20 | 0,373021 |

p=0.37>α avec α=0,05; les variances des différences entre les deux groupes sont les mêmes

On peut donc faire un test paramétrique, notamment l’ANOVA à mesure répété

ANOVA à mesure répété

Es ce que la [chlo a] varie selon la dose ?

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’ - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Tous les effets/graphs - Sélectionner ‘’dose’’

p=0.03<α avec α=0,05Il y a une différence significative entre les concentrations moyennes des différentes doses.La [chlo a] varie donc selon la dosep=0.03<α avec α=0,05Il y a une différence significative entre les concentrations moyennes des différentes doses.La [chlo a] varie donc selon la dose

Es ce que la [chlo a] varie selon le temps ?

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’ - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Tous les effets/graphs - Sélectionner ‘’temps’’

p=0.009<α avec α=0,05Il y a une différence significative entre les concentrations moyennes des différentes jours.La [chlo a] varie donc selon le jourp=0.009<α avec α=0,05Il y a une différence significative entre les concentrations moyennes des différentes jours.La [chlo a] varie donc selon le jour

Il y a t’il une interaction entre la dose et temps ?

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’ - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Tous les effets/graphs - Sélectionner ‘’TEMPS*dose’’

p=0.4>α avec α=0,05Il n’y a donc pas d’interaction statistiquement significative entre la dose et le temps.p=0.4>α avec α=0,05Il n’y a donc pas d’interaction statistiquement significative entre la dose et le temps.

L’objectif est déterminer la dose optimale de déjections pour une bonne production d’algue

Comparons donc les doses entre elles

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’ - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Autres résultats - Post hoc - Effets ‘’dose’’ - LSD de Fisher

| Test LSD ; variable VD_1 (Feuille de données32) Probabilités pour les Tests Post Hoc Erreur : MC Inter = ,00024, dl = 12,000 |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|
|  | dose | {1} | {2} | {3} | {4} | {5} | {6} |
| 1 | d0 |  | 0,337345 | 0,216001 | 0,046739 | 0,004954 | 0,009946 |
| 2 | d300 | 0,337345 |  | 0,764302 | 0,246981 | 0,031496 | 0,061979 |
| 3 | d600 | 0,216001 | 0,764302 |  | 0,380580 | 0,054812 | 0,105377 |
| 4 | d900 | 0,046739 | 0,246981 | 0,380580 |  | 0,246981 | 0,416766 |
| 5 | d1200 | 0,004954 | 0,031496 | 0,054812 | 0,246981 |  | 0,713481 |
| 6 | d1500 | 0,009946 | 0,061979 | 0,105377 | 0,416766 | 0,713481 |  |

Interprétation

| Doses | d0 | d300 | d600 | d900 | d1200 | d1500 |
|---|---|---|---|---|---|---|
| Moyennes | 0.005a | 0.010ac | 0.012ab | 0.016bc | 0.022b | 0.020bc |

Les moyennes suivie de différentes lettres sont significativement différentes au seuil de 5% (p <0.05)

Comparons donc le temps

Statistique - ANOVA - ANOVA mesures répétées - Insérer dans variable (dépendantes: ‘’j0-j18’’ et catégorielle: ‘’dose’’ - Effet intra (nbr de niveau: 7; nom du facteur: TEMPS) - Codes facteurs (tous) - Valider - Synthèse - Autres résultats - Post hoc - Effets ‘’TEMPS’’ - LSD de Fisher

| Test LSD ; variable VD_1 (Feuille de données1) Probabilités pour les Tests Post Hoc Erreur : MC Intra = ,00017, dl = 72,000 |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|
|  | TEMPS | {1} | {2} | {3} | {4} | {5} | {6} | {7} |
| 1 | j0 |  | 0,100363 | 0,026144 | 0,007301 | 0,014578 | 0,797098 | 0,969230 |
| 2 | j3 | 0,100363 |  | 0,546131 | 0,276406 | 0,404419 | 0,163901 | 0,092846 |
| 3 | j6 | 0,026144 | 0,546131 |  | 0,625404 | 0,817001 | 0,047870 | 0,023780 |
| 4 | j9 | 0,007301 | 0,276406 | 0,625404 |  | 0,797098 | 0,014578 | 0,006557 |
| 5 | j12 | 0,014578 | 0,404419 | 0,817001 | 0,797098 |  | 0,027833 | 0,013179 |
| 6 | j15 | 0,797098 | 0,163901 | 0,047870 | 0,014578 | 0,027833 |  | 0,767499 |
| 7 | j18 | 0,969230 | 0,092846 | 0,023780 | 0,006557 | 0,013179 | 0,767499 |  |

Interpretation

| Temps | J0 | J3 | J6 | J9 | J12 | J15 | J18 |
|---|---|---|---|---|---|---|---|
| Moyennes | 0.02a | 0.013ab | 0.010b | 0.008b | 0.009b | 0.192a | 0.02a |

Les moyennes suivie de différentes lettres sont significativement différentes au seuil de 5% (p <0.05)
