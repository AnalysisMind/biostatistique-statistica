# EXERCICE D’APPLICATION 13: Régression (variables quantitatives continues)

Dans le cadre d’une étude portant sur l’influence d’un antibiotique sur une culture bactérienne, on a voulu établir préalablement, une droite de calibration permettant d’estimer la concentration en bactérie. Le résultat obtenu est présenté dans le tableau ci-dessous :

| DO | 0,2 | 0,2 | 0,4 | 0,4 | 0,6 | 0,6 | 0,8 | 0,8 | 1 | 1 |
|---|---|---|---|---|---|---|---|---|---|---|
| [Bactérie] | 19 | 21 | 35 | 38 | 64 | 66 | 115 | 130 | 200 | 210 |

A partir de l’analyse judicieuse de ces données :

Vérifier si la densité optique permet d’estimer la concentration bactérienne.

Si oui, établir l’équation de la droite de calibration.

Apprécier la qualité globale de l’ajustement ainsi réalisé.

Quelle serait l’écart entre la concentration estimée et celle mesurée pour un échantillon dont la mesure de DO indique 0,6 ?

## RESULTAT

### Dispositif expérimentale

On est en présence de deux variables quantitative continue (do et [bactérie])

On cherche à vérifier si la densité optique permet d’estimer la concentration bactérienne

### Choix du test

Etant donné qu’on est en présence de variables quantitatives, nous ferons une analyse de corrélation

Etude de la linéarité de la relation entre les deux variables

Nuage de points

Graphiques - Nuage de points - Bases - Insérer les variables (x=DO et y=[Bactérie]) - Avancé - Cocher corrélation et p (aj. Linéaire)

(Visualisation) Nous constatons qu’il y a une corrélation linéaire entre la densité optique et la [Bactérie].

Etant donné que la corrélation est linéaire on peut faire une corrélation de Pearson

(Coefficient de Pearson) r=0,95 et p=0,000<α=0.05, alors r est significativement différent de zéro ; il y a donc une bonne corrélation linéaire entre la densité optique et la [Bactérie].

On peut conclure que la densité optique permet d’estimer la concentration bactérienne

Regression

Testons le modèle linéaire avec ordonée à l’origine

Analyse des coefficients de la régression

Statistiques - Modèles linéaires/ Non linéaires avancés - Modèle linéaire générale - Regression simple - Insérer les variables (dépendante=[Bactérie] et regresseur=DO) - Valider puis choisir Synthèse - Coefficients

dépendante=[Bactérie] et regresseur=DO car on cherche à écrire la [Bactérie] en fonction de la DO, donc la variable la plus difficile à évaluer est la [Bactérie] (dépendante) et celle facile à évaluer est la régresseur donc DO

| Paramètres Estimés (Feuille de données1) Paramétrisation sigma-restreint |  |  |  |  |
|---|---|---|---|---|
|  | [Bactérie] param. | [Bactérie] err-type | [Bactérie] t | [Bactérie] p |
| Ord.Orig. | -47 | 16,42 | -2,86 | 0,02 |
| DO | 228 | 24,75 | 9,21 | 0,00 |

On a :

a=228 et p= 0,00<α, donc a est significativement différent de zéro

b= -47 et p=0,02<α donc b est significativement différent de zéro

On a donc une équation de type y=ax+b tel que

[Bactérie]= 228*DO - 47

Apprécier la qualité globale de l’ajustement ainsi réalisé

Statistiques - Modèles linéaires/ Non linéaires avancés - Modèle linéaire générale - Regression simple - Insérer les variables (dépendante=DO et regresseur=[Bactérie]) - Valider puis choisir Synthèse – R modèle complet

| Test de SC Modèle Complet vs. SC Résidus (Feuille de données1) |  |  |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|---|---|
|  | Multiple | Multiple | Ajusté R2 | SC | dl | MC | SC | dl | MC | F | p |
| [Bactérie] | 0,96 | 0,91 | 0,90 | 41587,20 | 1,00 | 41587,20 | 3920,40 | 8,00 | 490,05 | 84,86318 | 0,000016 |

r2= 0,90 donc le modèle établit explique 91% de la variance totale.

F=84,86 et p=0,00 <α donc F est significativement différent de un et la variance expliqué est significativement supérieur à la variance inexpliqué.

Ecart entre la concentration estimée et celle mesurée pour un échantillon dont la mesure de DO indique 0,6

[Bactérie]= 228*DO - 47 donc [Bactérie]= 228* (0,6) -47 = 89,8 (estimation)

Pour DO=0,6 on a dans le tableau [Bactérie] (valeur mesuré)= 66 et 64 avec comme valeur moyenne =65 ((66+64)/2)

Ƹ=yi (estimé) - yi (mesuré) = 89,8 – 65= 24,8

Dans le but d'évaluer l’influence du pH sur la présence ou l’absence d’une plante Circaea lutetiana (CILU) et éventuellement prévoir la présence ou l’absence de cette plante en fonction du pH, Thoen (année) a relevé au niveau de 36 mardelles le pH, et les données de présence (1)/ absence (0) de cette plante. Les données sont présentées dans le tableau ci-contre:Peut-on affirmer que le pH influence la présence ou l’absence de cette plante? Le cas échéant, établir un modèle permettant de prévoir la présence ou l’absence de cette plante en fonction du pH, et discuter de la qualité de l’ajustementDans le but d'évaluer l’influence du pH sur la présence ou l’absence d’une plante Circaea lutetiana (CILU) et éventuellement prévoir la présence ou l’absence de cette plante en fonction du pH, Thoen (année) a relevé au niveau de 36 mardelles le pH, et les données de présence (1)/ absence (0) de cette plante. Les données sont présentées dans le tableau ci-contre:Peut-on affirmer que le pH influence la présence ou l’absence de cette plante? Le cas échéant, établir un modèle permettant de prévoir la présence ou l’absence de cette plante en fonction du pH, et discuter de la qualité de l’ajustement
