# EXERCICE D’APPLICATION 21: Classification Ascendante Hiérarchisée (CAH)

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

Regroupez entre eux les variables similaires selon la composition chimique de l’air

## RESULTATS

### Dispositif expérimentale

Variables quantitatives (concentration : SO2, CO2, O3, NO2)

Variables qualitatives nominales (villes)

On cherche à regrouper entre eux les variables similaires selon la composition chimique de l’air

### Mise en place du test

### Centrer et réduire les variables de départ

Données – Centrée et réduire – Insérer les variables (SO2, CO2, O3, NO2)

| villes | SO2 | CO2 | O3 | NO2 |
|---|---|---|---|---|
| Arlon | -0,792460342 | -0,540562478 | 0,098437404 | -0,837646757 |
| Liège | 0,629904375 | 0,72074997 | -0,787499231 | 0,815603421 |
| Namur | -0,914377318 | 0,360374985 | -0,492187019 | -1,43281682 |
| Bruxelles | 1,03629429 | 1,44149994 | 1,57499846 | -0,176346686 |
| Mons | -0,995655302 | -1,08112496 | 0,689061827 | 0,484953386 |
| Charleroi | 1,03629429 | -0,900937463 | -1,08281144 | 1,14625346 |

Changer les noms des observations par le nom des villes afin que les résultats qui s’afficheront après le test mettre le nom des villes et non le nom des observations (1,2,3,….)

### Mesurer les distances entre les individus

Techniques Exploratoires Multivariées – Classifications – Classifications hiérarchiques – Insérer les variables (SO2, CO2, O3, NO2) – Dans Avancé choisir (voire image) – valider – Choisir dendrogramme horizontale ou dendrogramme verticale

Saut minimum ou DiamètreObservations (lignes)Saut minimum ou DiamètreObservations (lignes)

Dendrogramme horizontaleDendrogramme verticaleDendrogramme horizontaleDendrogramme verticale

Il semble exister tout d'abord une classe constituée de la ville de Arlon et celle de Namur; viennent ensuite respectivement, la ville de Mons, et une classe formée par la ville de Liège et celle de Charleroi et enfin la ville de Bruxelles. La ville de Mons rejoint la première classe (formée de Arlon et Namur) à une distance d'agrégation d'environ 1,5594. Ensuite, les classes formées respectivement par les villes de Arlon, Namur et Mons d’une part puis Liège et Charleroi d’autre part, se rejoignent à une distance d’agrégation de 2,6706. Enfin, la ville de Bruxelles rejoint les cinq précédentes villes à une distance d'agrégation d'environ 2,6926. (voire les distances dans le tableau d’agrégation final plus bas)

Agrégation finale

Techniques Exploratoires Multivariées – Classifications – Classifications hiérarchiques – Insérer les variables (SO2, CO2, O3, NO2) – Dans Avancé choisir (voire image) – valider – Choisir Agrégation finale (dans avancé)

Saut minimum ou DiamètreObservations (lignes)Saut minimum ou DiamètreObservations (lignes)

| Agrégation Finale (Feuille) Saut Minimum Dist. Euclidiennes |  |  |  |  |  |  |
|---|---|---|---|---|---|---|
|  | Objet # 1 | Objet # 2 | Objet # 3 | Objet # 4 | Objet # 5 | Objet # 6 |
| 1,236777 | Arlon | Namur |  |  |  |  |
| 1,55936 | Arlon | Namur | Mons |  |  |  |
| 1,729613 | Liège | Charleroi |  |  |  |  |
| 2,670609 | Arlon | Namur | Mons | Liège | Charleroi |  |
| 2,692581 | Arlon | Namur | Mons | Liège | Charleroi | Bruxelles |

### Afficher le graphique de l’agrégation finale

Techniques Exploratoires Multivariées – Classifications – Classifications hiérarchiques – Insérer les variables (SO2, CO2, O3, NO2) – Dans Avancé choisir (voire image) – valider – Choisir Graphique de l’agrégation finale (dans avancé)

Si ce tracé fait apparaître un plateau, c'est l'indication que de nombreuses classes sont formées à cette distance d'agrégation. Cette distance peut alors constituer la distance d'élagage optimale pour définir le nombre de classes à retenir (même interprétation que pour le tableau).
