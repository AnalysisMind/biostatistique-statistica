# EXERCICE D’APPLICATION 14: Régression binomiale (variables qualitative dichotomique)

| pH | CILU |
|---|---|
| 5,9 | 1 |
| 6,9 | 1 |
| 6,6 | 1 |
| 6,2 | 0 |
| 6,4 | 0 |
| 6 | 0 |
| 7,2 | 1 |
| 7,1 | 0 |
| 7,3 | 0 |
| 7,5 | 0 |
| 7,2 | 1 |
| 6 | 0 |
| 7,1 | 0 |
| 7,4 | 0 |
| 7,4 | 1 |
| 7,4 | 1 |
| 7,2 | 1 |
| 6,3 | 0 |
| 6,6 | 0 |
| 7,4 | 0 |
| 6,9 | 1 |
| 6,7 | 0 |
| 7,1 | 0 |
| 7,5 | 1 |
| 7,1 | 1 |
| 6 | 0 |
| 6,6 | 0 |
| 7,6 | 1 |
| 7,5 | 1 |
| 6 | 0 |
| 7,4 | 0 |
| 7,7 | 1 |
| 8 | 1 |
| 7,6 | 1 |
| 8,1 | 1 |
| 7,7 | 1 |

## RESULTATS

Peut-on affirmer que le pH influence la présence ou l’absence de cette plante?

### Dispositif expérimentale

On est en présence d’une valeur qualitative dichotomique (la présence ou l’absence d’une plante Circaea lutetiana (CILU))

On a également une variable quantitative continue (pH)

On cherche à savoir si le pH influence la présence ou l’absence de cette plante

### Choix du test

On ne peut pas étudier une régression linéaire car n’étant pas adapté à des données dichotomiques

On peut donc se tourner vers une étude de régréssion binomiale notamment la régression logit

### Mise en place du test

Statistiques - Modèles linéaires/ Non linéaires avancés – Estimation non linéaire – Regression logit - Insérer les variables (dépendantes (c’est la variable dichotomique)= CILU, indépendantes= pH) - Valider 2 fois – Valeurs observées, prévus et résidus (pour voir si le logiciel à bien enregister nos données) – Si ce n’est le cas cliquer sur annuler puis changer les codes de la variables (0 deviendra 1 et 1 deviendra 0) – Valider (puis aller vérifier à nouveau les valeurs observées) - Valeurs observées, prévus et résidus - (Si c’est bon visualisont la courbes) – Base – Fonction 2D ajustée et valeurs observées.

On constate que plus le pH augmente plus le CILU est présent

On retourne dans Base – Synthèse: Paramètres estimés

| Modèle : Rég. logistique (logit) Nbe de 0 : 18 1 : 18 (Feuille de données24) Var dép. : CILU Perte : Max vraisemblance Perte finale : 20,366934553 Chi²( 1)=9,1727 p=,00246 |  |  |
|---|---|---|
|  | Const.B0 | PH |
| Estimat. | -13,8490 | 1,96701 |
| Odds ratio (unité) | 0,0000 | 7,14927 |
| Odds r. (étendue) |  | 75,74893 |

Chi2 =9,17 et p=0,002<α, donc les variables sont dépendantes

On continue l’analyse en allant dans Résidus – Classification d’obs et odds ratio

| Classification d'obs. (Feuille de données24) Odds ratio : 4,3750 Pourc. corrigé : 66,67% |  |  |  |
|---|---|---|---|
|  | Prév. 0,000000 | Prév. 1,000000 | % Corrigé |
| 0,000000 | 10 | 8 | 55,55556 |
| 1,000000 | 4 | 14 | 77,77778 |

Pour les observations ‘’0’’ 10 sont bien classés et 8 mal classées, soit 55,56% de correction

Pour les observations ‘’1’’ 14 sont bien classés et 4 mal classées, soit 77,78% de correction

De plus Odds ratio =4,3750 ≠ 1 donc les variables sont dépendantes.

Le pH influence donc la présence ou l’absence de cette plante

Etablissons un modèle permettant de prévoir la présence ou l’absence de cette plante en fonction du pH, et discutons de la qualité de l’ajustement

Modèle

Logit (p) = Ln (= B0 + B1X=0 or X= pH;

| Modèle : Rég. logistique (logit) Nbe de 0 : 18 1 : 18 (Feuille de données24) Var dép. : CILU Perte : Max vraisemblance Perte finale : 20,366934553 Chi²( 1)=9,1727 p=,00246 |  |  |
|---|---|---|
|  | Const.B0 | PH |
| Estimat. | -13,8490 | 1,96701 |
| Odds ratio (unité) | 0,0000 | 7,14927 |
| Odds r. (étendue) |  | 75,74893 |

B0 est la constante donc B0= -13,849

On a donc -13,849 + 1,96 pH= 0
