# EXERCICE D’APPLICATION 19: Analyse en composantes principales (ACP) (uniquement chez les variables quantitatives)

Considérons un tableau simple, avec seulement 4 variables sur 6 observations concernant l'analyse de 4 composés chimiques dans l'air de 6 villes belges. Pour ce cas d'école, les données sont fictives et les unités quelconques

Composition chimiques de l'air dans 6 villes belges

| Ville | SO2 | CO2 | O3 | NO2 |
|---|---|---|---|---|
| Arlon | 15 | 90 | 100 | 60 |
| Liège | 50 | 160 | 70 | 110 |
| Namur | 12 | 140 | 80 | 42 |
| Bruxelles | 60 | 200 | 150 | 80 |
| Mons | 10 | 60 | 120 | 100 |
| Charleroi | 60 | 70 | 60 | 120 |

Testez une classification de ces villes selon leurs profils atmosphériques basés sur ces quatre gaz

## RESULTATS

### Dispositif expérimentale

Variables quantitatives (concentration : SO2, CO2, O3, NO2)

Variables qualitatives nominales (villes)

On cherche à classer ces villes selon leurs profils atmosphériques en se basant sur ces 4 gaz ; à visualiser les liaisons entre plusieurs variables en un seul coup d'œil

### Centrer et réduire les valeurs des variables

Données – Centrée et réduire – Insérer les variables (SO2, CO2, O3, NO2)

| villes | SO2 | CO2 | O3 | NO2 |
|---|---|---|---|---|
| Arlon | -0,792460342 | -0,540562478 | 0,098437404 | -0,837646757 |
| Liège | 0,629904375 | 0,72074997 | -0,787499231 | 0,815603421 |
| Namur | -0,914377318 | 0,360374985 | -0,492187019 | -1,43281682 |
| Bruxelles | 1,03629429 | 1,44149994 | 1,57499846 | -0,176346686 |
| Mons | -0,995655302 | -1,08112496 | 0,689061827 | 0,484953386 |
| Charleroi | 1,03629429 | -0,900937463 | -1,08281144 | 1,14625346 |

### Valeurs propres (critère global: part d’inertie expliquée par chaque axe)

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – valeurs propres (dans variables)

| Val. Propres (matrice de corrél.) & stat. associées (Feuille) Variables actives seules |  |  |  |  |
|---|---|---|---|---|
|  | Val. propr | % Total variance | Cumul val. propr | Cumul % |
| 1 | 1,67 | 41,77 | 1,67 | 41,77 |
| 2 | 1,52 | 37,97 | 3,19 | 79,74 |
| 3 | 0,70 | 17,41 | 3,89 | 97,15 |
| 4 | 0,11 | 2,85 | 4 | 100 |

On constate que les facteurs 1 et 2 reproduisent 80% de la variance totale

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Tracé des valeurs propres (dans variables)

### Extraction des facteurs

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – vecteur propres (dans variables)

| Vecteurs propres de la matrice de corrélation (Feuille) Variables actives seules |  |  |  |  |
|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 |
| SO2 | 0,65 | 0,39 | -0,08 | 0,64 |
| CO2 | 0,01 | 0,75 | -0,42 | -0,51 |
| O3 | -0,30 | 0,51 | 0,80 | 0,09 |
| NO2 | 0,69 | -0,15 | 0,43 | -0,56 |

Au niveau du facteur 1: SO2 et NO2 sont fortement corrélé au facteur 1

Au niveau du facteur 2 : CO2 et O3 sont fortement corrélé au facteur 2

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Projection des variables 2D (dans variables)

la proximité de deux variables (comme SO2 et NO2, situés tous les deux à droite de l'axe "Facteur 1" indique une bonne corrélation entre elles;

2 variables éloignées l'une de l'autre (comme SO2 et O3) sont peu liées entre elles mais, deux variables diamétralement opposées par rapport à l'origine (comme NO2 et O3) peuvent témoigner d'une bonne corrélation négative ;

la position d'une variable près de l'origine des deux axes factoriels signifierait qu'elle n'est corrélée à aucun des deux facteurs, et donc, qu'elle ne prend pas une part importante dans le problème la position des variables par rapport aux directions factorielles peut aider à trouver un sens physique à ces deux facteurs (ici, par exemple, le premier facteur oppose NO2 et SO2 à O3 et le second oppose CO2 et NO2).

Cosinus carrés (critères individuels (ACP à la française))

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Cosinus 2 (dans individus)

| Cosinus carrés, basées sur les corrélations (Feuille) Var. illustrative : villes |  |  |  |  |  |
|---|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 | villes |
| 1 | 0,78 | 0,18 | 0 | 0,04 | Arlon |
| 2 | 0,68 | 0,03 | 0,18 | 0,11 | Liège |
| 3 | 0,63 | 0 | 0,36 | 0 | Namur |
| 4 | 0 | 0,95 | 0,04 | 0 | Bruxelles |
| 5 | 0,1 | 0,29 | 0,58 | 0,03 | Mons |
| 6 | 0,74 | 0,23 | 0 | 0,03 | Charleroi |

On en déduit que Arlon, Liège, Namur et Charleroi sont bien projetés sur l’axe défini par le facteur 1 alors que Bruxelles est plutôt bien projetée sur l’axe défini par le facteur 2

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Projection des individus 2D (dans individus)

La proximité de deux observations, comme Arlon et Namur, reflète une similitude de comportement des deux villes relativement à la qualité de l'air.

### Coordonnées factorielles (Proximité entre les individus et cercle de corrélation)

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Coordonnées des individus (dans individus)

| Coordonnées factorielles des ind., basées sur les corrélations (Feuille) Var. illustrative : villes |  |  |  |  |  |
|---|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 | villes |
| 1 | -1,1 | -0,54 | 0 | 0,25 | Arlon |
| 2 | 1,2 | 0,26 | -0,6 | -0,49 | Liège |
| 3 | -1,4 | -0,13 | -1,1 | -0,01 | Namur |
| 4 | 0,1 | 2,32 | 0,5 | 0,16 | Bruxelles |
| 5 | -0,5 | -0,92 | 1,3 | -0,29 | Mons |
| 6 | 1,8 | -1 | -0,1 | 0,39 | Charleroi |

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : SO2, CO2, O3, NO2 ; variables illustratives : villes) – valider – Coordonnées des variables (dans variables)

| Coord. factorielles des var., basées sur les corrélations (Feuille) |  |  |  |  |
|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 |
| SO2 | 0,84 | 0,49 | -0,06 | 0,22 |
| CO2 | 0,01 | 0,92 | -0,35 | -0,17 |
| O3 | -0,39 | 0,63 | 0,66 | 0,03 |
| NO2 | 0,9 | -0,19 | 0,36 | -0,19 |

## Tips : Angle aigu: variables positivement liées ; Angle droit: variables non liées ; Angle obtus: variables négativement liées

## En résumé

On est donc partie du tableau initial à l’obtention des informations redistribuées de manière à en concentrer un maximum (ici 80%) sur les deux premières dimensions

Ces deux graphes nous montrent que la ville de Bruxelles est plus riche en CO2 et O3; Liège, Namur, Arlon, Mons et Chaleroi sont riches en NO2 et SO2.
