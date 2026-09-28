# Prédiction des prix Airbnb

Ce projet de **Machine Learning** avait pour objectif de prédire le `log_price` de logements Airbnb à partir des caractéristiques présentes dans les annonces.

## Préparation des données

Les données brutes ont été nettoyées et transformées afin d'être exploitables par les différents modèles.

J'ai notamment travaillé sur :

- les caractéristiques du logement ;
- les équipements disponibles ;
- le type de logement et de chambre ;
- les informations relatives à l'hôte ;
- la localisation ;
- les descriptions textuelles.

Certaines variables textuelles ont ainsi été transformées en variables numériques, notamment la présence d'équipements ou la longueur des descriptions.

## Modélisation

Plusieurs approches ont été comparées :

- Régression linéaire
- Descente de gradient
- ACP suivie d'une régression
- Arbre de décision

Les performances ont été évaluées à l'aide de la **RMSE**, de la **MAE** et du **R²**.

## Résultats

Le meilleur modèle obtenu est un **arbre de décision de profondeur 10**, avec :

- **RMSE : 0,449**
- **MAE : 0,325**
- **R² : 0,610**

L'analyse du modèle permet également d'identifier les variables ayant le plus d'influence sur le prix, notamment la capacité d'accueil, le type de chambre, le nombre de chambres, la localisation et les équipements.

## Technologies

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn
