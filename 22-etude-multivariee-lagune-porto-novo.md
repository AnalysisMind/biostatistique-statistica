# EXERCICE D’APPLICATION 22

Pour caractériser la lagune de Porto-novo, Marcel mesuré 17 paramètres physico-chimiques en 15 stations choisies sur la base de la pression anthropique qu’elles subissent. Les résultats obtenus sont présentés dans le tableau ci-dessous:

Indiquer les variables qui ne sont pas pertinentes à prendre en compte dans le cadre de cette étude

Étudier la corrélation entre les paramètres physicochimiques mesurés

Étudier la similarité entre les stations

Indiquer les profils physico-chimiques des stations S4, S7, S9 et S13

Donner un modèle linéaire basés sur ces variables et expliquant 24% de la variance totale.

| Station | pH | Transparence | Conductivité | Salinité | Profondeur | Température | Turbidité | TDS | MES | P_redox | O2 | Chla | Pt | Ntk | DCO | DBO |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| S1 | 4,48 | 13,69 | 159,14 | 168,33 | 2,57 | 9,52 | 95,12 | 131,57 | 92,49 | 471,81 | 52,93 | 75,46 | 32,42 | 43,64 | 68,45 | 58,68 |
| S2 | 2,79 | 53,27 | 161,18 | 170,08 | 9,56 | 9,35 | 125,76 | 134,84 | 127,45 | 450,77 | 36,03 | 50,68 | 81,59 | 79,32 | 42,36 | 44,22 |
| S3 | 5,19 | 79,18 | 148,73 | 155,35 | 86,83 | 9,43 | 133,82 | 121,63 | 142,88 | -179,09 | 78,96 | 89,61 | 72,54 | 40,94 | 53,63 | 44,85 |
| S4 | 2,76 | 71,24 | 188,2 | 200 | 54,21 | 6,48 | 112,33 | 177,41 | 118,48 | - 4088,47 | 64,5 | 40,53 | 26,47 | 42,53 | 56,85 | 54,76 |
| S5 | 8,14 | 56,95 | 130,43 | 134,27 | 15,04 | 7,65 | 92,09 | 105,96 | 99,22 | -394,13 | 57,85 | 47,59 | 57,26 | 33,21 | 40,15 | 38,72 |
| S6 | 3,65 | 5,72 | 125,03 | 127,66 | 10,27 | 9,06 | 105,41 | 107,83 | 102,06 | -100,2 | 100,63 | 45,5 | 41,58 | 40,77 | 50,37 | 53,5 |
| S7 | 8,82 | 18,16 | 133,64 | 136,96 | 8,6 | 8,56 | 102,33 | 110,21 | 118,84 | -2051 | 97,18 | 55,19 | 52,79 | 27,95 | 28,35 | 23,56 |
| S8 | 5,25 | 9,61 | 124,18 | 125,32 | 9,94 | 9,23 | 147,87 | 103,43 | 151,83 | -162,23 | 51,34 | 70,08 | 106,27 | 59,67 | 19,91 | 32,26 |
| S9 | 7,15 | 2,67 | 122,86 | 126,74 | 11,37 | 9,26 | 120,18 | 107,22 | 110,14 | -426,36 | 71,66 | 72,81 | 100,32 | 34,07 | 57,34 | 59,72 |
| S10 | 7,06 | 27,51 | 115,55 | 124,19 | 12,84 | 7,46 | 130,6 | 107,67 | 145,93 | -393,35 | 52,48 | 90,33 | 58,73 | 36,7 | 86,48 | 73,68 |
| S11 | 7,42 | 46,01 | 111,93 | 124,19 | 56,04 | 8,51 | 104,51 | 109,53 | 117,8 | -411,65 | 41,54 | 64,84 | 92,98 | 54,15 | 125,42 | 105,02 |
| S12 | 6,4 | 32,62 | 135,3 | 115,53 | 65,32 | 10,19 | 130,92 | 181,11 | 124,75 | -151,24 | 38,84 | 60,41 | 97,92 | 24,72 | 60,52 | 64,28 |
| S13 | 3,83 | 12,57 | 116,37 | 151,44 | 15,49 | 8,61 | 93,31 | 136,81 | 90,43 | 4255,39 | 61,21 | 78,02 | 118,65 | 41,19 | 93,59 | 95,08 |
| S14 | 3,47 | 63,19 | 122,32 | 193,99 | 55,82 | 7,8 | 107,2 | 110,38 | 119,41 | -419,9 | 40,97 | 77,16 | 68,54 | 63,44 | 50,04 | 35,48 |
| S15 | 3,52 | 29,29 | 113,25 | 200 | 12,85 | 10,86 | 83,12 | 128,97 | 102,07 | 134,82 | 55,15 | 76,7 | 84,16 | 65,44 | 54,48 | 52,83 |

## RESULTATS 3

### Indiquons les variables qui ne sont pas pertinentes à prendre en compte dans le cadre de cette étude

### Dispositif expérimentale

Variables quantitatives continue (pH, Transparence, Conductivité, Salinité, Profondeur, Température, Turbidité)

Variable qualitative (station)

On veut analyser la corrélation entre ces différentes variables

Faisons un test ACP pour déterminer les variables qui ne sont pas pertinentes

### Centrer et réduire les valeurs des variables

Données – Centrée et réduire – Insérer les variables (pH,……)

| Station | pH | Trans | Cond | Sal | Prfd | Temp | Turb | TDS | MES | P_redox | O2 | Chla | Pt | Ntk | DCO | DBO |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| S1 | -0,42 | -0,84 | 1,17 | 0,61 | -0,96 | 0,65 | -0,93 | 0,27 | -1,33 | 0,42 | -0,36 | 0,58 | -1,45 | -0,14 | 0,35 | 0,13 |
| S2 | -1,25 | 0,73 | 1,26 | 0,67 | -0,70 | 0,49 | 0,73 | 0,40 | 0,52 | 0,41 | -1,22 | -0,99 | 0,32 | 2,18 | -0,64 | -0,52 |
| S3 | -0,07 | 1,76 | 0,69 | 0,17 | 2,17 | 0,56 | 1,16 | -0,13 | 1,34 | 0,03 | 0,95 | 1,48 | -0,01 | -0,32 | -0,21 | -0,49 |
| S4 | -1,27 | 1,45 | 2,51 | 1,68 | 0,96 | -2,07 | 0,00 | 2,11 | 0,05 | -2,29 | 0,22 | -1,64 | -1,67 | -0,22 | -0,09 | -0,05 |
| S5 | 1,39 | 0,88 | -0,16 | -0,54 | -0,50 | -1,03 | -1,09 | -0,77 | -0,97 | -0,10 | -0,11 | -1,19 | -0,56 | -0,82 | -0,72 | -0,77 |
| S6 | -0,83 | -1,15 | -0,41 | -0,76 | -0,67 | 0,23 | -0,37 | -0,69 | -0,82 | 0,08 | 2,05 | -1,32 | -1,12 | -0,33 | -0,33 | -0,10 |
| S7 | 1,72 | -0,66 | -0,01 | -0,45 | -0,74 | -0,21 | -0,54 | -0,60 | 0,07 | -1,08 | 1,87 | -0,71 | -0,72 | -1,16 | -1,17 | -1,45 |
| S8 | -0,04 | -1,00 | -0,45 | -0,84 | -0,69 | 0,39 | 1,92 | -0,87 | 1,81 | 0,04 | -0,44 | 0,24 | 1,20 | 0,90 | -1,49 | -1,06 |
| S9 | 0,90 | -1,28 | -0,51 | -0,79 | -0,63 | 0,41 | 0,43 | -0,72 | -0,39 | -0,12 | 0,58 | 0,41 | 0,99 | -0,77 | -0,07 | 0,18 |
| S10 | 0,85 | -0,29 | -0,85 | -0,88 | -0,58 | -1,20 | 0,99 | -0,70 | 1,50 | -0,10 | -0,38 | 1,52 | -0,51 | -0,60 | 1,03 | 0,80 |
| S11 | 1,03 | 0,45 | -1,01 | -0,88 | 1,02 | -0,26 | -0,42 | -0,62 | 0,01 | -0,11 | -0,94 | -0,09 | 0,72 | 0,54 | 2,51 | 2,21 |
| S12 | 0,53 | -0,09 | 0,07 | -1,17 | 1,37 | 1,24 | 1,01 | 2,26 | 0,38 | 0,05 | -1,07 | -0,38 | 0,90 | -1,37 | 0,05 | 0,38 |
| S13 | -0,74 | -0,88 | -0,81 | 0,04 | -0,48 | -0,17 | -1,03 | 0,48 | -1,44 | 2,67 | 0,06 | 0,74 | 1,65 | -0,30 | 1,30 | 1,76 |
| S14 | -0,92 | 1,13 | -0,53 | 1,48 | 1,02 | -0,89 | -0,28 | -0,59 | 0,10 | -0,11 | -0,97 | 0,69 | -0,15 | 1,14 | -0,35 | -0,91 |
| S15 | -0,89 | -0,22 | -0,95 | 1,68 | -0,58 | 1,84 | -1,58 | 0,16 | -0,82 | 0,22 | -0,25 | 0,66 | 0,41 | 1,27 | -0,18 | -0,13 |

### Valeurs propres (critère global: part d’inertie expliquée par chaque axe)

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : ph,….. ; variables illustratives : station) – valider – valeurs propres (dans variables)

| Val. Propres (matrice de corrél.) & stat. associées (Feuille1) Variables actives seules |  |  |  |  |
|---|---|---|---|---|
|  | Val. propr | % Total variance | Cumul val. propre | Cumul % |
| 1 | 3,837 | 23,98 | 3,84 | 24 |
| 2 | 2,832 | 17,7 | 6,67 | 41,7 |
| 3 | 2,582 | 16,14 | 9,25 | 57,8 |
| 4 | 2,145 | 13,41 | 11,4 | 71,2 |
| 5 | 1,292 | 8,07 | 12,69 | 79,3 |
| 6 | 0,945 | 5,91 | 13,63 | 85,2 |
| 7 | 0,751 | 4,69 | 14,38 | 89,9 |
| 8 | 0,524 | 3,28 | 14,91 | 93,2 |
| 9 | 0,458 | 2,86 | 15,37 | 96 |
| 10 | 0,314 | 1,96 | 15,68 | 98 |
| 11 | 0,186 | 1,16 | 15,86 | 99,2 |
| 12 | 0,1 | 0,63 | 15,96 | 99,8 |
| 13 | 0,03 | 0,19 | 15,99 | 100 |
| 14 | 0,005 | 0,03 | 16 | 100 |

On constate que les facteurs 1 et 2 reproduisent 41,7% de la variance totale

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : ph,….. ; variables illustratives : station) – valider – Projection des variables 2D (dans variables)

On constate que ‘’Turb’’ et ‘’MES’’ sont très proches du centre donc ces deux variables ne sont pas pertinentes à prendre en compte dans le cadre de cette étude.

### Étudions la corrélation entre les paramètres physicochimiques mesurés

### Mise en place du test

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : ph,….. ; variables illustratives : station) – valider – Projection des variables 2D (dans variables)

Ntk, Prfd, tDS, Sal, Trans, Cond sont fortement corrélées entre elles

DBO, DCO, Temp, Chla, P_redox, Pt, sont fortement corrélées entre elles

pH et O2 sont fortement corrélées entre elles

### Étudions la similarité entre les stations

### Mise en place du test

La station étant une variable quantitative et assez important en terme de nombre il serait plus judicieux de faire une analyse en composantes principales (ACP) afin d’étudier la similarité entre elles

### Centrer et réduire les valeurs des variables

### Valeurs propres (critère global: part d’inertie expliquée par chaque axe)

Cosinus carrés (critères individuels (ACP à la française))

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : pH, Transparence, Conductivité, Salinité, Profondeur, Température, Turbidité….; variables illustratives : stations) – valider – Cosinus 2 (dans individus)

| Cosinus carrés, basées sur les corrélations (Feuille1) Var. illustrative : Station |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 | Fact. 5 | Fact. 6 | Fact. 7 | Fact. 8 | Fact. 9 | Fact.10 | Fact.11 | Fact.12 | Fact.13 | Fact.14 | Station |
| 1 | 0,003 | 0,014 | 0,515 | 0 | 0,016 | 0,004 | 0,099 | 0,24 | 0,004 | 0,083 | 0,001 | 0,016 | 0,002 | 0 | S1 |
| 2 | 0,175 | 0,209 | 0,002 | 0,351 | 0,017 | 0,173 | 0,003 | 0,005 | 0 | 0,049 | 0,01 | 0,005 | 0 | 0,001 | S2 |
| 3 | 0,079 | 0,015 | 0,423 | 0 | 0,004 | 0,398 | 0,012 | 0,021 | 0 | 0,04 | 0,006 | 0 | 0 | 0 | S3 |
| 4 | 0,82 | 0,014 | 0,008 | 0,108 | 0,005 | 0,012 | 0,013 | 0,001 | 0 | 0,016 | 0,002 | 0 | 0 | 0 | S4 |
| 5 | 0,022 | 0,306 | 0,087 | 0,061 | 0,078 | 0,02 | 0,282 | 0,003 | 0,098 | 0,035 | 0,002 | 0,001 | 0,005 | 0,001 | S5 |
| 6 | 0,002 | 0,337 | 0,294 | 0,004 | 0,014 | 0 | 0,057 | 0,197 | 0,038 | 0,006 | 0,051 | 0 | 0 | 0 | S6 |
| 7 | 0,02 | 0,89 | 0,016 | 0 | 0,001 | 0,018 | 0,014 | 0,003 | 0,001 | 0,006 | 0,016 | 0,005 | 0,008 | 0 | S7 |
| 8 | 0,035 | 0,061 | 0,344 | 0,468 | 0,005 | 0,068 | 0,005 | 0,002 | 0,001 | 0,008 | 0 | 0,002 | 0,001 | 0,002 | S8 |
| 9 | 0,514 | 0,297 | 0,003 | 0,001 | 0,029 | 0 | 0,002 | 0,002 | 0,001 | 0,025 | 0,048 | 0,063 | 0,013 | 0,001 | S9 |
| 10 | 0,163 | 0,026 | 0,26 | 0,086 | 0,153 | 0,034 | 0,178 | 0,069 | 0,001 | 0,002 | 0,007 | 0,02 | 0,001 | 0 | S10 |
| 11 | 0,239 | 0,137 | 0,03 | 0,327 | 0,074 | 0,044 | 0,038 | 0,014 | 0,09 | 0,003 | 0,003 | 0,001 | 0,001 | 0 | S11 |
| 12 | 0,01 | 0,022 | 0,207 | 0,092 | 0,563 | 0,004 | 0,061 | 0,016 | 0 | 0,002 | 0,024 | 0 | 0 | 0 | S12 |
| 13 | 0,464 | 0,185 | 0,161 | 0,025 | 0,017 | 0,001 | 0,017 | 0,024 | 0,096 | 0,004 | 0,005 | 0,001 | 0,001 | 0 | S13 |
| 14 | 0,152 | 0,224 | 0,008 | 0,086 | 0,364 | 0,027 | 0,024 | 0 | 0,03 | 0,025 | 0,042 | 0,016 | 0,002 | 0,001 | S14 |
| 15 | 0,026 | 0,189 | 0,273 | 0,259 | 0,003 | 0,083 | 0,034 | 0,019 | 0,067 | 0,034 | 0 | 0,012 | 0,002 | 0 | S15 |

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : pH, Transparence, Conductivité, Salinité, Profondeur, Température, Turbidité…….; variables illustratives : stations) – valider – Projection des individus 2D (dans individus) – Cocher ‘’étiquette illustrative’’

La proximité de deux observations, comme Arlon et Namur, reflète une similitude de comportement des deux villes relativement à la qualité de l'air.

On constate que les stations 13, 11, 15 présentent une similitude__On constate que les stations 1, 12, et 3 présentent une similitude__On constate que les stations 1 et 2 présentent une similitude__On constate que les stations 10, 9 et 8 présentent une similitude__On constate que les stations 5, 7 et 6 présentent une similitude

### Indiquons les profils physico-chimiques des stations S4, S7, S9 et S13

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : pH, Transparence, Conductivité, Salinité, Profondeur, Température, Turbidité; variables illustratives : stations) – valider – Projection des variables 2D (dans variables) – ensuite faire Projection des individus 2D (dans individus)

On constate que S4 possède une importante conductivité

S7 possède une faible conductivité

S9 possède une faible conductivité

S13 possède une importante température et un pH important

Donner un modèle linéaire basés sur ces variables et expliquant 24% de la variance totale.

Le facteur 1 explique 24% de la variance totale (voire le tableau de valeurs propres plus haut)

Statistique – Techniques Exploratoires multivariées – ACP ‘’à la française’’ – Insérer les variables (variable actives : pH, Transparence, Conductivité, Salinité, Profondeur, Température, …….( sans turbidité et MES); variables illustratives : stations) – valider – coordonnées des variables (dans variables)

| Coord. factorielles des var., basées sur les corrélations (Feuille1) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|  | Fact. 1 | Fact. 2 | Fact. 3 | Fact. 4 | Fact. 5 | Fact. 6 | Fact. 7 | Fact. 8 | Fact. 9 | Fact.10 | Fact.11 | Fact.12 | Fact.13 | Fact.14 |
| pH | -0,4 | -0,6 | -0,46 | -0,3 | -0,15 | 0,22 | -0,2 | -0,1 | 0,05 | 0,16 | 0,18 | 0,02 | 0,05 | -0,01 |
| Trans | 0,63 | 0,41 | -0,3 | -0,49 | -0,07 | 0,02 | 0,13 | 0,07 | 0,18 | 0,16 | 0,06 | -0,11 | -0,03 | 0 |
| Cond | 0,84 | 0,08 | -0,07 | 0,29 | -0,09 | -0,02 | -0,16 | 0,08 | 0,26 | -0,2 | 0,2 | 0,06 | -0,01 | 0 |
| Sal | 0,61 | 0,49 | 0,35 | -0,03 | 0,22 | -0,27 | -0,08 | -0,03 | -0,21 | 0,24 | 0,14 | 0,07 | -0,01 | 0 |
| Prfd | 0,29 | 0,42 | -0,55 | -0,36 | -0,43 | -0,2 | 0,24 | -0,05 | -0,02 | -0,08 | -0,11 | 0,1 | 0,02 | -0,01 |
| Temp | -0,4 | 0,14 | 0,49 | 0,18 | -0,57 | -0,17 | -0,01 | -0,4 | 0,15 | 0,09 | 0,01 | 0 | -0,03 | 0 |
| TDS | 0,45 | 0,42 | -0,27 | 0,56 | -0,42 | 0,02 | -0,13 | 0,07 | -0,15 | 0,06 | -0,02 | -0,08 | 0,06 | 0 |
| P_redox | -0,71 | 0,36 | 0,26 | 0,19 | 0,02 | -0,14 | 0,09 | 0,37 | 0,26 | 0,16 | -0,04 | 0,03 | 0,03 | 0 |
| O2 | 0,08 | -0,72 | 0 | 0,14 | 0,05 | -0,54 | 0,38 | -0,01 | -0,02 | -0,03 | 0,14 | -0,05 | 0,03 | 0 |
| Chla | -0,52 | 0,32 | 0,04 | -0,4 | -0,02 | -0,52 | -0,39 | 0,07 | -0,03 | -0,15 | 0,02 | -0,05 | 0,01 | 0 |
| Pt | -0,69 | 0,36 | 0,13 | -0,1 | -0,39 | 0,24 | 0,19 | 0,19 | -0,19 | -0,09 | 0,22 | 0,01 | -0,02 | 0,01 |
| Ntk | 0,13 | 0,58 | 0,62 | -0,23 | 0,25 | 0,25 | 0,15 | -0,19 | 0,05 | -0,12 | 0,05 | -0,03 | 0,07 | -0,01 |
| DCO | -0,44 | 0,49 | -0,6 | 0,15 | 0,36 | -0,08 | 0,02 | -0,2 | 0,05 | 0,03 | 0,05 | 0,03 | 0,03 | 0,02 |
| DBO | -0,52 | 0,49 | -0,53 | 0,34 | 0,26 | -0,01 | 0,08 | -0,11 | 0 | -0,04 | 0,06 | -0,03 | -0,05 | -0,02 |

Facteur 1= -0,4pH + 0,63Trans……

Ou on peut prendre les valeurs ayant de forte correlation sur le facteur 1 (-1 <valeurs< -0,5 et 0,5
