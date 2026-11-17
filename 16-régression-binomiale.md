# EXERCICE D’APPLICATION 16: Régression binomiale

Dans le but de déterminer la dose létale d’un toxique donné pour la moitié de la population, différentes doses ont été testées sur des groupes d’individus, le tableau ci-contre résume les observations réalisées:

| Doses appliqués | Nombres d’individus testés | Nombre de décès observé |
|---|---|---|
| 50 | 102 | 19 |
| 60 | 121 | 26 |
| 70 | 111 | 24 |
| 80 | 105 | 31 |
| 90 | 117 | 54 |
| 100 | 108 | 83 |

### Déterminer la DL50

## RESULTAT

### Déterminons la DL50

### Dispositif expérimentale

On est en présence d’une valeur qualitative dichotomique (la survie ou le décès)

On a également deux variables quantitatives discontinue (dose et nombre d’individus)

On cherche à déterminer la DL50

### Choix du test

On ne peut pas étudier une régression linéaire car n’étant pas adapté à des données dichotomiques

On peut donc se tourner vers une étude de régression binomiale notamment la régression Probit ou logit

### Insérer ce tableau dans statistica

| Dose | Etat | Nombre d'individus |
|---|---|---|
| 50 | décès | 19 |
| 50 | survie | 83 |
| 60 | décès | 26 |
| 60 | survie | 95 |
| 70 | décès | 24 |
| 70 | survie | 87 |
| 80 | décès | 31 |
| 80 | survie | 74 |
| 90 | décès | 54 |
| 90 | survie | 63 |
| 100 | décès | 83 |
| 100 | survie | 25 |

### Mise en place du test (probit)

On utiliser les données de dilution/100 car elles sont plus facilement manipulables

Statistiques - Modèles linéaires/ Non linéaires avancés – Estimation non linéaire – Regression probit - Dans fichier d’entrée comporte mettre ‘’codes et effectifs’’ - Insérer les variables (dépendantes (c’est la variable dichotomique)= Etat, indépendantes= dose, effectif= Nombre d’individus) - Valider 2 fois – Valeurs observées, prévus et résidus (pour voir si le logiciel à bien enregister nos données) – Si ce n’est le cas cliquer sur annuler puis changer les codes de la variables (décès deviendra survie et survie deviendra décès) – Valider (puis aller vérifier à nouveau les valeurs observées) - Valeurs observées, prévus et résidus - (Si c’est bon visualisont la courbes) – Base – Fonction 2D ajustée et valeurs observées.

Plus la dose augmente plus il y a de décès

On continue l’analyse en allant dans Résidus – Classifaication d’obs et odds ratio

| Classification d'obs. (Feuille) Odds ratio : 5,2776 Pourc. corrigé : 71,69% |  |  |  |
|---|---|---|---|
|  | Prév. survie | Prév. décès | % |
| survie | 339 | 88 | 79,3911 |
| décès | 100 | 137 | 57,80591 |

Pour les observations ‘’survie’’ 339 sont bien classés et 88 mal classées, soit 79,39% de correction

Pour les observations ‘’décès’’ 137 sont bien classés et 100 mal classées, soit 57,80% de correction

De plus Odds ratio =5,2 ≠ 1 donc les variables sont dépendantes.

On continue l’analyse en allant dans Base – Synthèse: Paramètres estimés

| Modèle : Régression Probit Nbe de 0 : 427 1 : 237 (Feuille) Var dép. : Etat Perte : Max vraisemblance Perte finale : 383,76686578 Chi²( 1)=97,831 p=0,0000 |  |  |
|---|---|---|
|  | Const.B0 | dose |
| Estimat. | -2,70334 | 0,030543 |

La dose influence donc négativement (car B1= -2,7) l’état physiologique avec comme équation y=NC(-2,70334 + 0,030543x;0;1); x=dose

0pargument0,50pargument0,5Dans la loi normale réduite cumulée p vaut 0,5 lorsque l’argument vaut 0

On posera donc y=0= -2,70334 + 0,030543x

Ainsi x= 2,70334 / 0,030543 = 88,509

DL50= 88,509

Pour la régression logit on trouve

| Modèle : Rég. logistique (logit) Nbe de 0 : 427 1 : 237 (Feuille) Var dép. : Etat Perte : Max vraisemblance Perte finale : 382,90584451 Chi²( 1)=99,553 p=0,0000 |  |  |
|---|---|---|
|  | Const.B0 | dose |
| Estimat. | -4,57002 | 0,05162 |
| Odds ratio (unité) | 0,01036 | 1,05297 |
| Odds r. (étendue) |  | 13,20882 |

On aura le modèle -4,57002 + 0,05162x= 0

-4,57002 + 0,05162x= 0 dose= = 88,53196435

Les résultats sont semblables
