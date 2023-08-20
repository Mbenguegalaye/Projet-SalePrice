# Projet-SalePrice

                    INTRODUCTION

Ce mémoire présente une étude approfondie menée dans le cadre du Data Challenge Kaggle axé sur la prédiction du prix des maisons (SalePrice). L'objectif central réside dans la création de modèles d'apprentissage automatique de haute précision pour évaluer les valeurs des propriétés résidentielles. À travers une exploration méthodique et une analyse rigoureuse, cette étude vise à relever le défi complexe de la prédiction des prix immobiliers.

                     Développement

La première phase de l'étude se concentre sur la préparation minutieuse des données. L'ensemble de données contient une variété de variables explicatives décrivant les propriétés, avec comme variable cible le prix final de chaque maison (SalePrice). Les données manquantes sont gérées en supprimant certaines variables et en imputant des valeurs pour d'autres. De plus, les variables catégorielles sont transformées en données numériques à l'aide de techniques d'encodage appropriées.

Le graphique ci-dessous offre une illustration visuelle des données, permettant une meilleure compréhension.

![Données](https://github.com/Mbenguegalaye/Projet-SalePrice/assets/141923523/2c58c5ee-fbdb-41ac-81a6-7fedf1cc7927) <br>

Une observation clé est faite lors de l'analyse de la distribution de la variable cible, révélant une distribution asymétrique à droite. Pour résoudre ce problème, plusieurs transformations sont explorées, notamment le Johnson Transform et le Log-normal.

Le graphique ci-dessous illustre la variable cible et les transformations effectuées.

![Transformations](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Transformations.png) <br>

Trois modèles d'apprentissage automatique sont choisis pour la prédiction des prix : la Régression Linéaire, la Forêt Aléatoire et l'Amplification du Gradient. Chaque modèle est minutieusement ajusté et évalué en utilisant des métriques telles que le MAE, le MSE, le RMSE et le R2. Des graphiques de dispersion et des graphiques résiduels sont utilisés pour illustrer visuellement les performances de chaque modèle.

 Ci-dessous sont présentées les performances et les graphiques relatifs à la Régression Linéaire

 ![Regression-lineaire](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/images/Regression-lineaire.png) <br>

 Ci-dessous sont présentées les performances et les graphiques relatifs à la Foret Aléatire

 ![Foret Aléatoire](https://github.com/Mbenguegalaye/Projet-SalePrice/assets/141923523/1acbb9d8-db09-4ec9-b23a-42595dd2484b) <br>

Ci-dessous sont présentées les performances et les graphiques relatifs à l'Amplification du Gradient

![GradientBoosting](https://github.com/Mbenguegalaye/Projet-SalePrice/assets/141923523/3e0d2894-250e-4a11-849f-f1c272aff2dd) <br>

Les résultats révèlent que la Forêt Aléatoire et l'Amplification du Gradient surpassent la Régression Linéaire en termes de précision de prédiction, avec une meilleure capacité à capturer les nuances non linéaires des données. Cependant, chaque modèle présente des avantages et des limitations spécifiques.

                          CONCLUSION

En conclusion, cette étude a illuminé l'essentielle préparation des données dans l'édification de modèles d'apprentissage automatique à la pointe de l'efficacité. Les découvertes et les perspectives tirées de cette aventure au sein du Data Challenge Kaggle s'érigent en bases inébranlables pour le choix judicieux et l'amélioration continue des modèles de prévision des prix des habitations.
L'analyse minutieuse de l'ensemble de données, la gestion ingénieuse des valeurs manquantes, et la transformation éclairée des variables catégorielles en données numériques constituent les piliers fondamentaux ayant pavé la voie à des modèles affinés. L'observation de la distribution asymétrique à droite de la variable cible, 'SalePrice', a déclenché des investigations approfondies et des ajustements judicieux tels que le Johnson Transform et le Log-normal, pour mieux adapter les modèles à la réalité des données.
En étudiant de près les performances et les caractéristiques distinctes de trois modèles - la Régression Linéaire, la Forêt Aléatoire et l'Amplification du Gradient -, nous avons appréhendé que la complexité et la non-linéarité inhérentes aux données requièrent des outils de prédiction sophistiqués. Les modèles tels que la Forêt Aléatoire et l'Amplification du Gradient ont prouvé leur supériorité en offrant des prédictions plus précises et en capturant de façon plus fidèle les nuances du jeu de données.
Finalement, cette étude nous rappelle l'importance de l'exploration approfondie des données, de l'ajustement adéquat des modèles et de l'évaluation rigoureuse de leurs performances. Elle ouvre également la voie à des investigations futures, explorant d'autres algorithmes sophistiqués et se plongeant davantage dans les spécificités du marché immobilier à Ames, Iowa. En unissant rigueur méthodologique et adaptation à l'évolution du domaine, nous érigeons les fondations pour une amélioration constante des modèles de prédiction et pour des découvertes encore plus captivantes dans le domaine de l'analyse prédictive.

Mots clés : Data Challenge Kaggle, prédiction de prix, nettoyage des données, transformations, modèles d'apprentissage automatique.

Pour faciliter la compréhension et la réplication de cette étude, nous mettons à votre disposition les données utilisées pour l'apprentissage et la validation du modèle. Vous trouverez ci-dessous les liens vers les ensembles de données d'entraînement et de validation :

[données train](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/train/train.csv)<br>
[données test](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/test/test.csv)<br>
[données sample_submission](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/sample_submission/sample_submission.csv)<br>

Les résultats de nos tests sont disponibles dans le dossier 'submission' de ce dépôt. Vous pouvez accéder aux fichiers de résultats en suivant ce lien: 
[](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/submission/submission.csv)<br>

