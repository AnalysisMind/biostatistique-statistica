# EXERCICE D’APPLICATION 15: Régression binomiale

| Dilution | Dilution/100 | Réponse |
|---|---|---|
| 100 | 1 | 1 |
| 100 | 1 | 1 |
| 100 | 1 | 1 |
| 100 | 1 | 1 |
| 100 | 1 | 1 |
| 100 | 1 | 1 |
| 500 | 5 | 1 |
| 500 | 5 | 1 |
| 500 | 5 | 1 |
| 500 | 5 | 0 |
| 500 | 5 | 1 |
| 500 | 5 | 1 |
| 1000 | 10 | 1 |
| 1000 | 10 | 1 |
| 1000 | 10 | 0 |
| 1000 | 10 | 0 |
| 1000 | 10 | 1 |
| 1000 | 10 | 1 |
| 1200 | 12 | 1 |
| 1200 | 12 | 1 |
| 1200 | 12 | 0 |
| 1200 | 12 | 0 |
| 1200 | 12 | 0 |
| 1200 | 12 | 0 |
| 1500 | 15 | 1 |
| 1500 | 15 | 0 |
| 1500 | 15 | 0 |
| 1500 | 15 | 0 |
| 1500 | 15 | 1 |
| 1500 | 15 | 0 |
| 1800 | 18 | 1 |
| 1800 | 18 | 1 |
| 1800 | 18 | 0 |
| 1800 | 18 | 0 |
| 1800 | 18 | 0 |
| 1800 | 18 | 0 |
| 2000 | 20 | 0 |
| 2000 | 20 | 0 |
| 2000 | 20 | 0 |
| 2000 | 20 | 0 |
| 2000 | 20 | 0 |
| 2000 | 20 | 0 |
| 2500 | 25 | 0 |
| 2500 | 25 | 0 |
| 2500 | 25 | 0 |
| 2500 | 25 | 0 |
| 2500 | 25 | 0 |
| 2500 | 25 | 0 |
| 5000 | 50 | 0 |
| 5000 | 50 | 0 |
| 5000 | 50 | 0 |
| 5000 | 50 | 0 |
| 5000 | 50 | 0 |
| 5000 | 50 | 0 |

L'olfactométrie consiste à demander à un panel d'au moins 4 personnes de flairer plusieurs dilutions d'un mélange gazeux odorant prélevé sur le terrain. La réponse des membres du panel ne doit pas être dubitative : oui ou non l'odeur est ressentie. Une odeur ressentie sera codée par "1" et le code sera "0" dans le cas contraire. La dilution pour laquelle 50 % des membres du panel sentent l'odeur et 50 % ne sentent rien est considérée comme la "dilution au seuil de perception olfactive", qui permet de quantifier le niveau d'une odeur dans l'environnement. Soit une analyse olfactométrique à 6 personnes sur une odeur prélevée dans un centre de compostage de la fraction organique d'ordures ménagères. Le tableau suivant montre les observations brutes. la dose/dilution d’odeur influence-t-elle la réponse du panéliste? Si oui, établir un modèle entre la dose/dilution d’odeur et la réponse du panéliste Si oui, déterminer la "dilution au seuil de perception olfactive".L'olfactométrie consiste à demander à un panel d'au moins 4 personnes de flairer plusieurs dilutions d'un mélange gazeux odorant prélevé sur le terrain. La réponse des membres du panel ne doit pas être dubitative : oui ou non l'odeur est ressentie. Une odeur ressentie sera codée par "1" et le code sera "0" dans le cas contraire. La dilution pour laquelle 50 % des membres du panel sentent l'odeur et 50 % ne sentent rien est considérée comme la "dilution au seuil de perception olfactive", qui permet de quantifier le niveau d'une odeur dans l'environnement. Soit une analyse olfactométrique à 6 personnes sur une odeur prélevée dans un centre de compostage de la fraction organique d'ordures ménagères. Le tableau suivant montre les observations brutes. la dose/dilution d’odeur influence-t-elle la réponse du panéliste? Si oui, établir un modèle entre la dose/dilution d’odeur et la réponse du panéliste Si oui, déterminer la "dilution au seuil de perception olfactive". RESULTAT

Vérifions si la dose/dilution d’odeur influence la réponse du panéliste

### Dispositif expérimentale

On est en présence d’une valeur qualitative dichotomique (la présence ou l’absence d’odeur)

On a également une variable quantitative continue (dilution du mélange gazeux)

On a également une variable qualitative nominale (les personnes)

On cherche à savoir si la dilution influence la réponse du panéliste

### Choix du test

On ne peut pas étudier une régression linéaire car n’étant pas adapté à des données dichotomiques

On peut donc se tourner vers une étude de régression binomiale notamment la régression logit ou celle Probit

Celle probit et celle logit donnerons les mêmes résultats mais on pourra privilégier le probit car la présence /absence d’odeur n’est pas réellement établie ; une personne qui a faiblement sentie une odeur jugera bon mettre qu’il n’a rien sentie or qu’une autre personne fera l’inverse ; on est avec une variable dichotomique mais qui peut complètement varier, 1/0 ne pourra donc pas dire clairement si l’individu à réellement sentie l’odeur ou non

### Mise en place du test (probit)

On utiliser les données de dilution/100 car elles sont plus facilement manipulables

Statistiques - Modèles linéaires/ Non linéaires avancés – Estimation non linéaire – Regression probit - Insérer les variables (dépendantes (c’est la variable dichotomique)= Réponse, indépendantes= Dilution/100) - Valider 2 fois – Valeurs observées, prévus et résidus (pour voir si le logiciel à bien enregister nos données) – Si ce n’est le cas cliquer sur annuler puis changer les codes de la variables (0 deviendra 1 et 1 deviendra 0) – Valider (puis aller vérifier à nouveau les valeurs observées) - Valeurs observées, prévus et résidus - (Si c’est bon visualisont la courbes) – Base – Fonction 2D ajustée et valeurs observées.

Plus on dilue le mélange gazeux moins les personnes sentent d’odeur

On continue l’analyse en allant dans Résidus – Classifaication d’obs et odds ratio

| Classification d'obs. (Feuille de données24) Odds ratio : 25,000 Pourc. corrigé : 83,33% |  |  |  |
|---|---|---|---|
|  | Prév. 0,000000 | Prév. 1,000000 | % Corrigé |
| 0,000000 | 30 | 3 | 90,90909 |
| 1,000000 | 6 | 15 | 71,42857 |

Pour les observations ‘’0’’ 30 sont bien classés et 3 mal classées, soit 90,9% de correction

Pour les observations ‘’1’’ 15 sont bien classés et 6 mal classées, soit 71,42% de correction

De plus Odds ratio =25 ≠ 1 donc les variables sont dépendantes.

Statistiques - Modèles linéaires/ Non linéaires avancés – Estimation non linéaire – Regression probit - Insérer les variables (dépendantes (c’est la variable dichotomique)= Réponse, indépendantes= Dilution/100) - Valider 2 fois – Valeurs observées, prévus et résidus (pour voir si le logiciel à bien enregister nos données) – Si ce n’est le cas cliquer sur annuler puis changer les codes de la variables (0 deviendra 1 et 1 deviendra 0) – Valider (puis aller vérifier à nouveau les valeurs observées) - Valeurs observées, prévus et résidus - (Si c’est bon visualisont la courbes) – Base – Synthèse: Paramètres estimés

| Modèle : Régression Probit Nbe de 0 : 33 1 : 21 (Feuille de données24) Var dép. : réponse Perte : Max vraisemblance Perte finale : 19,812478734 Chi²( 1)=32,546 p=,00000 |  |  |
|---|---|---|
|  | Const.B0 | dilution/100 |
| Estimat. | 2,008492 | -0,169209 |

La dose/dilution d’odeur influence donc négativement (car B1= -0,17) la réponse du panéliste

Etablissons un modèle entre la dose/dilution d’odeur et la réponse du panéliste

y= NC (2,009 – 0,17x) avec x= dilution/100

### Déterminons la "dilution au seuil de perception olfactive"

La dilution pour laquelle 50 % des membres du panel sentent l'odeur et 50 % ne sentent rien est considérée comme la "dilution au seuil de perception olfactive" (voir énoncé)

0pargument0,50pargument0,5Dans la loi normale réduite cumulée p vaut 0,5 lorsque l’argument vaut 0

On posera donc 2,009 – 0,17 (dilution/100)= 0

2,009 – 0,17 (dilution/100)= 0 dilution = = 1187

La dilution au seuil de perception olfactive est de 1187 ou 11,84 (dilution/100)

### Mise en place du test (logit) – essayons la régression logit

Statistiques - Modèles linéaires/ Non linéaires avancés – Estimation non linéaire – Regression logit - Insérer les variables (dépendantes (c’est la variable dichotomique)= Réponse, indépendantes= Dilution/100) - Valider 2 fois – Valeurs observées, prévus et résidus (pour voir si le logiciel à bien enregister nos données) – Si ce n’est le cas cliquer sur annuler puis changer les codes de la variables (0 deviendra 1 et 1 deviendra 0) – Valider (puis aller vérifier à nouveau les valeurs observées) - Valeurs observées, prévus et résidus – retourné dans Résidus – Classification d’obs et odds ratio

| Classification d'obs. (Feuille de données24) Odds ratio : 25,000 Pourc. corrigé : 83,33% |  |  |  |
|---|---|---|---|
|  | Prév. 0,000000 | Prév. 1,000000 | % Corrigé |
| 0,000000 | 30 | 3 | 90,90909 |
| 1,000000 | 6 | 15 | 71,42857 |

Retounées dans Base – Synthèse: Paramètres estimés

| Modèle : Rég. logistique (logit) Nbe de 0 : 33 1 : 21 (Feuille de données24) Var dép. : réponse Perte : Max vraisemblance Perte finale : 19,981869546 Chi²( 1)=32,207 p=,00000 |  |  |
|---|---|---|
|  | Const.B0 | dilution/100 |
| Estimat. | 3,38967 | -0,285982 |
| Odds ratio (unité) | 29,65607 | 0,751277 |
| Odds r. (étendue) |  | 0,000001 |

Odds ratio =25 ≠ 1 et Chi²=32,207 donc les variables sont dépendantes

On aura le modèle 3,38 – 0,29 (dilution/100)= 0

3,38 – 0,29 (dilution/100)= 0 dilution= = 1165

Les résultats entre logit et probit sont semblables
