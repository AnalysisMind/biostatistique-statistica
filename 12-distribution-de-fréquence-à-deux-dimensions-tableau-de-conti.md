# EXERCICE D’APPLICATION 12: Distribution de fréquence à deux dimensions (tableau de contingence de type 3*2)

Considérons les données de McHugh (2013) relatives à l’effet d’un vaccin sur trois catégories de personnes et qui sont présentées dans le tableau de fréquence 3 x 2 ci-dessous.

| Résultats | Etat vaccinal |  |
|---|---|---|
|  | Non vacciné | Vacciné |
| Pneumonie de type pneumococcal | 23 | 5 |
| Pneumonie de type non pneumococcal | 8 | 10 |
| Sain | 61 | 77 |

Peut-on dire que la vaccination influence l’état de santé des individus au sein de cette population?

## RESULTATS

On est en présence de deux variables qualitatives (état vaccinal et état de santé).

### Insérer les données dans statistica

Faire le test de dépendance de chi-deux

Statistiques - Techniques exploratoires multivariés – Analyse des correspondances – Insérer les variables (état de santé et état vaccinal) – cocher tableau de contingence – Dans étude choisir effectif théorique – Validé

| Effectifs Théoriques (Feuille de données14) Table d'Entrée (Lignes x Colonnes) : 3 x 2 Inertie Totale = ,07418 Chi² = 13,649 dl = 2 p = ,00109 |  |  |  |
|---|---|---|---|
|  | nv | v | Total |
| pp | 14 | 14 | 28 |
| pnp | 9 | 9 | 18 |
| sain | 69 | 69 | 138 |
| Total | 92 | 92 | 184 |

On constate que p=0.001 < α=0.05, la vaccination influence donc l’état de santé des individus au sein de cette population

Faisons alors la contribution au chi deux pour savoir à quel niveau se manifeste cette influence

Statistiques - Techniques exploratoires multivariés – Analyse des correspondances – Insérer les variables (état de santé et état vaccinal) – cocher tableau de contingence – Dans étude choisir contribution au chi deux – Validé

| Contributions au Chi-Deux (Feuille de données14) Table d'Entrée (Lignes x Colonnes) : 3 x 2 Inertie Totale = ,07418 Chi² = 13,649 dl = 2 p = ,00109 |  |  |  |
|---|---|---|---|
|  | nv | v | Total |
| pp | 5,785714 | 5,785714 | 11,57143 |
| pnp | 0,111111 | 0,111111 | 0,22222 |
| sain | 0,927536 | 0,927536 | 1,85507 |
| Total | 6,824362 | 6,824362 | 13,64872 |

La conclusion ci-dessus (le statut vaccinal influence l’état de santé) peut être validé uniquement dans le cas ‘’pp (Pneumonie de type pneumococcal)’’ car ses Chi deux > 1.
