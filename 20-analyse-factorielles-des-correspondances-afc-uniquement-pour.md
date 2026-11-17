# EXERCICE D’APPLICATION 20: Analyse factorielles des correspondances (AFC) (uniquement pour les variables qualitatives)

| Pays | Engrais | Pays | Engrais | Pays | Engrais | Pays | Engrais |
|---|---|---|---|---|---|---|---|
| Bénin | E1 | Bénin | E3 | Mali | E2 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E2 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E2 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E2 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E2 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E3 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E3 | Burkina | E2 |
| Bénin | E1 | Bénin | E3 | Mali | E3 | Burkina | E3 |
| Bénin | E1 | Bénin | E3 | Mali | E3 | Burkina | E3 |
| Bénin | E1 | Bénin | E3 | Mali | E3 | Burkina | E3 |
| Bénin | E2 | Bénin | E3 | Mali | E3 | Burkina | E3 |
| Bénin | E2 | Bénin | E3 | Mali | E3 | Burkina | E4 |
| Bénin | E2 | Bénin | E4 | Mali | E4 | Burkina | E4 |
| Bénin | E2 | Bénin | E4 | Mali | E4 | Togo | E1 |
| Bénin | E2 | Bénin | E4 | Mali | E4 | Togo | E1 |
| Bénin | E2 | Bénin | E4 | Mali | E4 | Togo | E1 |
| Bénin | E2 | Bénin | E4 | Mali | E4 | Togo | E1 |
| Bénin | E2 | Bénin | E4 | Burkina | E1 | Togo | E3 |
| Bénin | E2 | Bénin | E4 | Burkina | E1 | Togo | E4 |
| Bénin | E2 | Bénin | E4 | Burkina | E1 | Togo | E4 |
| Bénin | E2 | Mali | E1 | Burkina | E1 | Togo | E4 |
| Bénin | E2 | Mali | E1 | Burkina | E1 | Togo | E4 |
| Bénin | E3 | Mali | E2 | Burkina | E1 | Togo | E4 |
| Bénin | E3 | Mali | E2 | Burkina | E1 | Togo | E4 |
| Bénin | E3 | Mali | E2 | Burkina | E1 | Togo | E4 |

Etudiez la dépendance (χ2) entre les variables qualitatives.

## RESULTATS

### Dispositif expérimentale

Variable qualitative nominale (engrais et pays)

On veut savoir s’il y dépendance entre les variables

### Mise en place du test

Mettre les données en groupe (une colonne pays et une autre: engrais) dans statistica

### Effectifs observés et théoriques

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – effectifs observés (dans étude) – Puis effectifs théoriques (Chi2) (dans étude)

| Table Observée (Effectifs) (Feuille) Variables ligne : Pays(4) Variables colonne : Engrais(4) |  |  |  |  |  |
|---|---|---|---|---|---|
|  | E1 | E2 | E3 | E4 | Total |
| Bénin | 10 | 12 | 15 | 8 | 45 |
| Mali | 2 | 8 | 7 | 5 | 22 |
| Burkina | 8 | 7 | 4 | 2 | 21 |
| Togo | 4 | 0 | 1 | 7 | 12 |
| Total | 24 | 27 | 27 | 22 | 100 |

| Effectifs Théoriques (Feuille) Variables ligne : Pays(4) Variables colonne : Engrais(4) |  |  |  |  |  |
|---|---|---|---|---|---|
|  | E1 | E2 | E3 | E4 | Total |
| Bénin | 10,8 | 12,15 | 12,15 | 9,9 | 45 |
| Mali | 5,28 | 5,94 | 5,94 | 4,84 | 22 |
| Burkina | 5,04 | 5,67 | 5,67 | 4,62 | 21 |
| Togo | 2,88 | 3,24 | 3,24 | 2,64 | 12 |
| Total | 24 | 27 | 27 | 22 | 100 |

### Calcul des profils lignes et des profils colonne

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Pourcentage ligne (dans étude) – Puis Pourcentage colonne (dans étude)

| Pourcentages des Totaux Ligne (Feuille) Variables ligne : Pays(4) Variables colonne : Engrais(4) |  |  |  |  |  |
|---|---|---|---|---|---|
|  | E1 | E2 | E3 | E4 | Total |
| Bénin | 22,22 | 26,67 | 33,33 | 17,78 | 100 |
| Mali | 9,09 | 36,36 | 31,82 | 22,73 | 100 |
| Burkina | 38,1 | 33,33 | 19,05 | 9,52 | 100 |
| Togo | 33,33 | 0 | 8,33 | 58,33 | 100 |

| Pourcentages des Totaux Colonne (Feuille) Variables ligne : Pays(4) Variables colonne : Engrais(4) |  |  |  |  |
|---|---|---|---|---|
|  | E1 | E2 | E3 | E4 |
| Bénin | 41,67 | 44,44 | 55,56 | 36,36 |
| Mali | 8,33 | 29,63 | 25,93 | 22,73 |
| Burkina | 33,33 | 25,93 | 14,81 | 9,09 |
| Togo | 16,67 | 0 | 3,7 | 31,82 |
| Total | 100 | 100 | 100 | 100 |

### Valeurs propres (Extraction des dimensions principales)

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Valeurs propres (dans avancé)

| Valeurs Propres et Inertie de toutes les Dimensions (Feuille) Table d'Entrée (Lignes x Colonnes) : 4 x 4 Inertie Totale = ,20494 Chi² = 20,494 dl = 9 p = ,01512 |  |  |  |  |  |
|---|---|---|---|---|---|
|  | ValSing. | ValProp. | %age inertie | %age cumulé | Chi² |
| 1 | 0,38 | 0,14 | 69,2 | 69 | 14,2 |
| 2 | 0,23 | 0,05 | 26,5 | 96 | 5,4 |
| 3 | 0,09 | 0,01 | 4,3 | 100 | 0,9 |

On constate que les dimensions 1 et 2 reproduisent 96% de l’inertie totale; Chi2=20,49 >1 avec p<0,05 ; il y a donc dépendance entre les variables.

Il apparaît ici qu'avec une seule dimension, 69,2% de l'inertie peut être "expliquée", c’-à-d que les valeurs des fréquences relatives qui peuvent être reconstruites à partir d'une seule dimension reproduisent 69,2% de la valeur totale du Chi² (et donc de l'inertie) pour ce tableau à double entrée ; deux dimensions nous permettent d'expliquer 96%.

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Tracé des valeurs propres (dans avancé)

### Coordonnées Lignes et Contributions à l’inertie

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Coordonées ligne colonne (dans avancé)

| Coordonnées Colonne et Contributions à l'Inertie (Feuille) Table d'Entrée (Lignes x Colonnes) : 4 x 4 Standardisation : Profils ligne et colonne |  |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|---|
|  | Colonne | Coord. dim.1 | Coord. dim.2 | Masse | Qualité | Inertie relative | Inertie dim.1 | Cosinus² dim.1 | Inertie dim.2 | Cosinus² dim.2 |
| Bénin | 1 | - 0,1 | 0,04 | 0,45 | 0,6 | 0,05 | 0,04 | 0,53 | 0,01 | 0,07 |
| Mali | 2 | - 0,2 | 0,3 | 0,22 | 0,89 | 0,14 | 0,05 | 0,22 | 0,36 | 0,67 |
| Burkina | 3 | - 0,2 | - 0,4 | 0,21 | 0,97 | 0,2 | 0,04 | 0,13 | 0,62 | 0,84 |
| Togo | 4 | 1 | 0 | 0,12 | 1 | 0,61 | 0,88 | 1 | 0 | 0 |

La première dimension représente fortement le Bénin et le Togo, la deuxième dimension représente fortement le Mali et Burkina.

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Tracé des coordonnés (dans avancé) – Lignes 2D

On constate que sur la première dimension (le plus important), le Bénin et le Togo sont bien représentés (cos2= 0,53 et 1) alors que le Mali et le Burkina sont mieux représentés sur la deuxième dimension (cos2= 0,67 et 0,84)

### Coordonnées colonnes et Contributions à l’inertie

| Coordonnées Colonne et Contributions à l'Inertie (Feuille) Table d'Entrée (Lignes x Colonnes) : 4 x 4 Standardisation : Profils ligne et colonne |  |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|---|
|  | Colonne numéro | Coord. dim.1 | Coord. dim.1 | Masse | Qualité | Inertie relative | Inertie dim.1 | Cosinus² dim.1 | Inertie dim.2 | Cosinus² dim.2 |
| E1 | 1 | 0,14703 | -0,39356 | 0,24 | 0,991892 | 0,208397 | 0,036598 | 0,121482 | 0,684262 | 0,87041 |
| E2 | 2 | -0,378122 | 0,011377 | 0,27 | 0,905258 | 0,208272 | 0,272314 | 0,904439 | 0,000643 | 0,000819 |
| E3 | 3 | -0,248066 | 0,175291 | 0,27 | 0,859542 | 0,141419 | 0,117203 | 0,573285 | 0,152711 | 0,286257 |
| E4 | 4 | 0,608107 | 0,200246 | 0,22 | 0,995727 | 0,441911 | 0,573885 | 0,898319 | 0,162383 | 0,097409 |

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Coordonées ligne colonne (dans avancé)

Il apparaît que :

- la 1ère dimension présente bien les engrais E2, E3 et E4 (cos2 respectivement, 0,90; 0,57 et 0,90). Elle oppose les engrais E2 et E3 à celui E4. (voire figure)

- E1 est bien représenté sur la dimension 2 (cos2=0,87).

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Tracé des coordonnés (dans avancé) – Colonnes 2D

### Compatibilité des points les lignes et colonnes

Statistique – Techniques Exploratoires multivariées – Analyse des correspondances – Insérer les variables (variable ligne : pays ; variables colonne : engrais) – codes des variables de classement (pays : tous ; engrais : tous) – cocher données brutes - valider – Tracé des coordonnés (dans avancé) – Ligne & Colonne 2D

Puisque la catégorie E4 est le seul point colonne à droite de l'origine sur le premier axe, et puisque le groupe Togo se trouve également de ce côté du premier axe, nous pouvons en conclure que le premier axe oppose E4 aux autres engrais, et que le Togo se différencie, par exemple, des autres pays, par une proportion de ce type d’engrais.
