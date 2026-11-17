# EXERCICE D’APPLICATION 2: Comparaison d’une moyenne à un standard

Pour obtenir une eau potable, on effectue en général un traitement en trois (03) étapes :

- d’abord, un traitement primaire, par sédimentation,

- ensuite un traitement secondaire, par oxydation biologique,

- enfin, un traitement tertiaire, par adsorption sur des résines, pour enlever le reste des composés chimiques.

Concernant l'atténuation des concentrations en composés chimiques, les deux premiers traitements apportent de bons résultats, exceptés pour les sulfates, qu'il faut tenter d'éliminer par un traitement tertiaire. Supposons donc que nous ayons mis au point une nouvelle résine échangeuse d'ions et que nous désirons tester si elle apporte effectivement une amélioration significative concernant la concentration résiduelle en sulfates dans l'eau par rapport aux deux premiers traitements (primaire et secondaire) et aussi par rapport aux autres résines habituellement utilisées.

Imaginons que nous ayons effectué 50 mesures de concentration en sulfates, dans l'eau traitée par notre nouvelle résine, utilisée comme traitement tertiaire. Nous obtenons par exemple, le tableau ci-dessous qui comprend 50 valeurs variant entre 9,8 et 17,7 mg/l : la moyenne des valeurs est 14,64 et la variance 3,41 (écart-type 1,848).

| sulf_mg_L |
|---|
| 17,74 |
| 12,17 |
| 12,22 |
| 13,89 |
| 16,47 |
| 15,88 |
| 16,1 |
| 16,74 |
| 17,54 |
| 17,43 |
| 14,57 |
| 12,9 |
| 12,81 |
| 14,95 |
| 16,25 |
| 17,13 |
| 14,46 |
| 14,2 |
| 16,9 |
| 11,34 |

Dans la littérature, nous apprenons que la valeur de concentration en sulfates typiquement atteinte après les deux premières étapes du traitement (et donc avant le traitement par la résine) est 16 mg/l. La concentration moyenne atteinte grâce à la résine que nous avons inventée est de 14,64 mg/l. Alors, pouvons-nous conclure que nous améliorons la situation par rapport à un traitement "simple" ?Dans la littérature, nous apprenons que la valeur de concentration en sulfates typiquement atteinte après les deux premières étapes du traitement (et donc avant le traitement par la résine) est 16 mg/l. La concentration moyenne atteinte grâce à la résine que nous avons inventée est de 14,64 mg/l. Alors, pouvons-nous conclure que nous améliorons la situation par rapport à un traitement "simple" ?

| sulf_mg_L |
|---|
| 14,94 |
| 13,66 |
| 9,79 |
| 13,08 |
| 14,57 |
| 14,93 |
| 14,01 |
| 14,43 |
| 16,35 |
| 15,65 |
| 11,52 |
| 17,46 |
| 14,67 |
| 15,92 |
| 16,02 |
| 13,46 |
| 13,7 |
| 14,98 |
| 14,57 |
| 15,72 |

## RESULTATS

On cherche à savoir si la valeur de concentration en sulfates typiquement atteinte après les deux premières étapes du traitement (et donc avant le traitement par la résine) 16 mg/l et la concentration moyenne atteinte grâce à la résine que nous avons inventée 14,64 mg/l sont significativement différents ou non.

Description du dispositif expérimentale

- On est présence d’une variable quantitative continue

- On veut comparé un échantillon 14,64 mg/l avec une valeur de référence 16 mg/l

### Choix du test approprié

- Etude de la normalité

avec la statistique descriptive

| Statistiques Descriptives (Feuille de données12) |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|
|  | N Actifs | Moyenne | Médiane | Mode | Effectif | Asymétrie | Aplatissement |
| [sulfates]mg/l | 50 | 14,64100 | 14,57000 | 14,57000 | 3 | -0,342865 | -0,322039 |

Mode ≈ médiane ≈ moyenne et coef d’asymétrie et d’aplatissement Ꞓ[-2;2]

La distribution suit une loi normale

avec le test de Shapiro-Wilk

P=0.429>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.P=0.429>α avec α=0,05Donc il n’y a aucune différence statistiquement significative entre la distribution et la loi normaleLa distribution suit donc une loi normale.

Test à utilisé

On peut utilisé un test paramétrique afin de comparer une moyenne à une valeur standard

On utilisera donc le test t de student car de plus c’est la variance de l’échantillon qui est connue et non celle de toute la population

| Comparaison de moyennes à un standard (constante) (Feuille de données12) |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|
|  | Moyenne | Ec-Type | N | Erreur-T | Valeur de | Valeur t | dl | p |
| [sulfates]mg/l | 14,64100 | 1,847799 | 50 | 0,261318 | 16,00000 | -5,20056 | 49 | 0,000004 |

t=-5,20; dl=49; p=0,000004<α avec α=0.05

Donc il y a une différence statistiquement significative entre la concentration en sulfates typiquement atteinte après les deux premières étapes du traitement (et donc avant le traitement par la résine) 16 mg/l et la concentration moyenne atteinte grâce à la résine que nous avons inventée 14,64 mg/l.

Notre résine améliore donc la situation par rapport à un traitement "simple".
