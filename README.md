# Projet-SalePrice
INTRODUCTION

Ce mémoire présente une étude approfondie menée dans le cadre du Data Challenge Kaggle axé sur la prédiction du prix des maisons (SalePrice). L'objectif de cette étude était de développer des modèles d'apprentissage automatique précis pour estimer les prix des maisons résidentielles.

Développement

L'étude débute par une description détaillée de l'ensemble de données, qui contient 79 variables explicatives décrivant divers aspects des propriétés immobilières. La variable cible est le prix final de chaque maison. Une étape cruciale de nettoyage des données est entreprise, impliquant la gestion des valeurs manquantes et la transformation des variables catégorielles en données numériques.

Le graphique ci-dessous offre une illustration visuelle des données, permettant une meilleure compréhension.



Une observation clé est faite lors de l'analyse de la distribution de la variable cible, révélant une distribution asymétrique à droite. Pour résoudre ce problème, plusieurs transformations sont explorées, notamment le Johnson Transform et le Log-normal.

Le graphique ci-dessous illustre la variable cible et les transformations effectuées.

![texte1](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Transformations.png) <br>

Trois modèles d'apprentissage automatique sont choisis pour la prédiction des prix : la Régression Linéaire, la Forêt Aléatoire et l'Amplification du Gradient. Chaque modèle est minutieusement ajusté et évalué en utilisant des métriques telles que le MAE, le MSE, le RMSE et le R2. Des graphiques de dispersion et des graphiques résiduels sont utilisés pour illustrer visuellement les performances de chaque modèle.

 Ci-dessous sont présentées les performances et les graphiques relatifs à la Régression Linéaire

 ![texte3](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Regression-lineaire.png) <br>

Ci-dessous sont présentées les performances et les graphiques relatifs au Foret Aléatoire

![image](https://github.com/Mbenguegalaye/Projet-SalePrice/assets/141923523/3e0d2894-250e-4a11-849f-f1c272aff2dd) <br>


 

Les résultats révèlent que la Forêt Aléatoire et l'Amplification du Gradient surpassent la Régression Linéaire en termes de précision de prédiction, avec une meilleure capacité à capturer les nuances non linéaires des données. Cependant, chaque modèle présente des avantages et des limitations spécifiques.

CONCLUSION

En conclusion, cette étude met en évidence l'importance cruciale de la préparation minutieuse des données dans la construction de modèles d'apprentissage automatique performants. Les résultats et les enseignements tirés de cette expérience de participation au Data Challenge Kaggle fournissent des bases solides pour la sélection et l'amélioration continue des modèles de prédiction de prix des maisons.

Mots clés : Data Challenge Kaggle, prédiction de prix, nettoyage des données, transformations, modèles d'apprentissage automatique.


[texte4](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Random%20Forest.png) <br>
[texte5](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Amplification%20du%20Gradient.png) <br>
[code](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/Codes/Projet_SalePrice%20(4).html) <br>
