# Projet de classe - Session automne 2023

Dans ce projet je cherche à découvrir et évaluer trois algorithmes d'apprentissage machine supervisés : les Réseau Neurones Artificiels (ANN), XGBoost, et RandomForest. Ces algorithmes proviennent de la bibliothèque scikit-learn en Python.

Selon l'énoncé du projet, les algoritmes doivent être utilisés sur deux bases de données.
- Le premier dataset contient des annonces immobilières du site realtor.com, basé à Santa Clara, Californie.
Source : https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset
- Le deuxième jeu de données provient de l'enquête Sloan Digital Sky Survey (SDSS) et comprend 100 000 
observations de l'espace. Chaque observation est décrite par 17 colonnes de caractéristiques et 
une colonne de classe, qui identifie l'objet observé comme étant une galaxie, une étoile ou un 
quasar.
Source : https://www.kaggle.com/datasets/fedesoriano/stellarclassification-dataset-sdss17.

Chaque algorithme est donc employé pour une classification (déterminer le type d’un objet céleste) et que pour une régression (prédire le prix d’un bien immobilier).   J’ai ensuite fait une analyse quantitative des modèles en mesurant plusieurs métriques (R2, RMSE et MAE pour la régression ; précision, rappel, et F1 pour la classification).
