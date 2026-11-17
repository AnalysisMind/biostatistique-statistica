# EXERCICE D’APPLICATION 18: Analyse multivarié (Régression multilinéaire (MLR) incrémentielle)

Imaginons que la variable qui nous intéresse le plus est la conductivité de l'eau de la source et que nous voulions savoir, parmi les 6 autres variables mesurées, quelles sont celles qui l'influencent le plus.

Testez une MLR incrémentielle.

## RESULTATS

### Dispositif expérimentale

Variables quantitatives continue (le débit de la source, le rayonnement solaire, la température de l'air, les précipitations, la température de l'eau, la conductivité électrique de la source d'eau, la hauteur du niveau d'eau de la nappe)

Variable qualitative (temps= 2 jours)

On veut tester une régression multilinéaire incrémentielle (afin d’émettre un modèle linéaire entre la variable dépendant et les régresseurs)

Statistique – régression multiple – insérer les variables (dépendantes: cond, indépendantes: débit-pluie-rayonnt-t air-t eau-nappe) – dans avancé cocher ‘’options avancées (régression rigide ou pas-à-pas)’’ – valider – dans base puis méthodes choisir ‘’pas-à-pas ascendante’’ – dans pas-à-pas mettre (voire image) - valider

On obtient le tableau ci contre

### Cliquer sur suivant pour voir les autres étapes

A chaque fois cliquer sur Synthèse: Résultats de la regression puis sur Synthèse de la régression pas-à-pas

| Synthèse de la Régression; Variable Dép. : cond (Feuille) R= ,97438442 R²= ,94942500 R² Ajusté = ,94888697 F(1,94)=1764,6 p<0,0000 Err-Type de l'Estim.: ,36103 |  |  |  |  |  |  |
|---|---|---|---|---|---|---|
|  | Bêta | Err-Type | B | Err-Type | t(94) | niveau p |
| OrdOrig. |  |  | 60,03631 | 0,268416 | 223,6692 | 0 |
| débit | -0,974384 | 0,023196 | -4,8404 | 0,115227 | -42,0074 | 0 |

| Synthèse Régression Pas-à-Pas ; VD: cond (Feuille) |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|
|  | Etape | R | R² | R² | F | Niveau p | Variables |
| débit | 1 | 0,974384 | 0,949425 | 0,949425 | 1764,626 | 0 | 1 |

### Cliquer sur suivant pour voir les autres étapes

### Etape 2

| Synthèse de la Régression; Variable Dép. : cond (Feuille) R= ,98060196 R²= ,96158021 R² Ajusté = ,96075398 F(2,93)=1163,8 p<0,0000 Err-Type de l'Estim.: ,31636 |  |  |  |  |  |  |
|---|---|---|---|---|---|---|
|  | Bêta | Err-Type | B | Err-Type | t(93) | niveau p |
| OrdOrig. |  |  | 59,78842 | 0,2396 | 249,5344 | 0 |
| débit | -0,943964 | 0,021085 | -4,68928 | 0,104742 | -44,77 | 0 |
| pluie | -0,11437 | 0,021085 | -0,3269 | 0,060266 | -5,4243 | 0 |

| Synthèse Régression Pas-à-Pas ; VD: cond (Feuille) |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|
|  | Etape | R | R² | R² | F | Niveau p | Variables |
| débit | 1 | 0,974384 | 0,949425 | 0,949425 | 1764,626 | 0 | 1 |
| pluie | 2 | 0,980602 | 0,96158 | 0,012155 | 29,423 | 0 | 2 |

Ainsi de suite jusqu’à l’étape 4 où on a

| Synthèse de la Régression; Variable Dép. : cond (Feuille) R= ,98438069 R²= ,96900534 R² Ajusté = ,96764294 F(4,91)=711,25 p<0,0000 Err-Type de l'Estim.: ,28725 |  |  |  |  |  |  |
|---|---|---|---|---|---|---|
|  | Bêta | Err-Type | B | Err-Type | t(91) | niveau p |
| OrdOrig. |  |  | 57,45415 | 0,699004 | 82,1943 | 0 |
| débit | -0,895591 | 0,035598 | -4,44898 | 0,176837 | -25,1586 | 0 |
| pluie | -0,133815 | 0,019855 | -0,38248 | 0,05675 | -6,7397 | 0 |
| t eau | 0,188353 | 0,048506 | 0,3509 | 0,090367 | 3,8831 | 0,000195 |
| nappe | -0,156196 | 0,06266 | -0,02773 | 0,011125 | -2,4928 | 0,014485 |

On pourra donc écrire ‘’cond’’ en fonction des autres variables que le logiciel a jugé capable de suffisamment influencer la variable dépendante ‘’cond’’

Cond= -4,44 Débit – 0,38 Pluie + 0,35 T eau – 0,028 Nappe + 57,45 ; les p des coefficients sont tous < α ; ils sont donc significativement différents de zéro

r2= 0,969 donc le modèle établit explique 97% de la variance totale.

F=711,25 et p=0,00 <α donc F est significativement différent de un et la variance expliqué est significativement supérieur à la variance inexpliqué.

| Synthèse Régression Pas-à-Pas ; VD: cond (Feuille) |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|
|  | Etape | R multiple | R² multiple | R² modif. | F | Niveau p | Variables |
| débit | 1 | 0,974384 | 0,949425 | 0,949425 | 1764,626 | 0 | 1 |
| pluie | 2 | 0,980602 | 0,96158 | 0,012155 | 29,423 | 0 | 2 |
| t eau | 3 | 0,983305 | 0,966889 | 0,005309 | 14,75 | 0,000225 | 3 |
| nappe | 4 | 0,984381 | 0,969005 | 0,002116 | 6,214 | 0,014485 | 4 |
