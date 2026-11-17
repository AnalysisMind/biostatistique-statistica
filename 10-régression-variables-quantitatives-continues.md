# EXERCICE D’APPLICATION 10: Régression (variables quantitatives continues)

Sur un échantillon de 15 enfants de 2 ans, on a mesuré la taille (en cm) et le poids (en kg) ; les données obtenues, sont présentées dans le tableau ci-dessous.

| Taille | Poids |
|---|---|
| 82,9 | 8,7 |
| 83,4 | 9,2 |
| 82,4 | 9,5 |
| 82,1 | 10,1 |
| 84,8 | 10,4 |
| 86,7 | 10,5 |
| 84 | 10,8 |
| 89 | 11 |
| 85 | 11,5 |
| 85,4 | 11,6 |
| 87,7 | 12,4 |
| 87,7 | 13,6 |
| 86,4 | 13,8 |
| 86,4 | 13,9 |
| 86,9 | 14,6 |

A partir d’une analyse judicieuse de ces données, vérifier s’il y a une relation linéaire entre la taille et le poids chez ces enfants et étudier la régression.

## RESULTATS

### Dispositif expérimentale

On est en présence de deux variables quantitative continue (poids et taille)

On cherche à vérifier s’il y a une relation linéaire entre les deux.

### Choix du test

Etude de la linéarité

Nuage de points

Graphiques - Nuage de points - Bases - Insérer les variables (x=poids et y=taille) - Avancé - Cocher corrélation et p (aj. Linéaire)

(Visualisation) Nous constatons qu’il y a une corrélation linéaire entre le poids et la taille des enfants.

(Coefficient de Pearson) r=0,67 et p=0.005<α=0,05, alors r est significativement différent de zéro ; il y a donc une bonne corrélation linéaire entre le poids et la taille des enfants.

Puisque la corrélation est linéaire on peut tester une régression.

Regression

Analyse des coefficients de la régression

Statistiques - Modèles linéaires/ Non linéaires avancés - Modèle linéaire générale - Regression simple - Insérer les variables (dépendante=poids et regresseur=taille) - Valider puis choisir Synthèse - Coefficients

|  | taille (param.) | taille Err-Type | taille t | taille p |
|---|---|---|---|---|
| Ord.Orig. | 76,55 | 2,687 | 28,49 | 0,000 |
| poids | 0,77 | 0,232 | 3,33 | 0,005 |

On a :

a=0,773 et p= 0,005<α, donc a est significativement différent de zéro

b= 76,546 et p=0,000<α donc b est significativement différent de zéro

On a donc une équation de type y=ax+b tel que

Taille= 0,773*Poids + 76,546

Analyse de la qualité de l’ajustement

Statistiques - Modèles linéaires/ Non linéaires avancés - Modèle linéaire générale - Regression simple - Insérer les variables (dépendante=poids et regresseur=taille) - Valider puis choisir Synthèse – R modèle complet

|  | Multiple R | Multiple R² | Ajusté R² | SC Modèle | dl Modèle | MC Modèle | SC Résidus | dl Résidus | MC Résidus | F | p |
|---|---|---|---|---|---|---|---|---|---|---|---|
| taille | 0,679 | 0,460 | 0,419 | 28,59 | 1 | 28,59 | 33,51 | 13 | 2,577 | 11,09 | 0,005 |

r2= 0.419, donc le modèle établit explique 41,9% de la variance totale.

F=11,09 et p=0.005 <α donc F est significativement différent de un et la variance expliqué est significativement supérieur à la variance inexpliqué.
