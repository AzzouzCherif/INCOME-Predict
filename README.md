# INCOME-Predict
Projet 7 - "Effectuez une prédiction de revenus" 
Le but du projet est de créer un modèle pour déterminer le revenu potentiel d'une personne.

Jeu de données :

country_code.csv : Liste des codes pays ISO3-3166 Alpha-3
data-projet7.csv: données de la World Income Distribution sur les revenus par quantile par pays et année
gdim.csv: données de la World Income Distribution sur les coefficients de mobilité intergénérationnelle de revenus
gini : données de la banque mondiale sur les indices de Gini par pays et année
population : données de la banque mondiale sur le nombre d'habitants par pays
A partir du jeu de données dans le fichier download_csv, le script "Partie1_P7.ipynb" va :
-Repérer et remplacer les valeurs manquantes par des données les plus cohérentes possibles
-Afficher des représentations graphiques des revenus et des indices de Gini
-Attribuer une classe de revenus parents en fonction des revenus d'une personne, selon une loi Normale, et grâce au coefficient d'élasticité.
-Créer un fichier analyse.csv

A partir du fichier analyse.csv, le script "Partie2_P7.ipynb" va :
-Effectuer différentes modélisations.
-Analyser la pertinence de ces modèles.

Il s'agit de fichiers jupyter notebook.
Les scripts principaux utilisent des fonctions attribuées dans deux fichiers : -functions1.py pour le script 1 -functions2.py pour le script 2
