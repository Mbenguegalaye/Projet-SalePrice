# Présentation d'un Projet sur la Prédiction des Prix des Maisons (SalePrice)

Mon tout premier projet sur la prédiction des prix des maisons, réalisé dans le cadre de mon mémoire de fin d'année du Master 1 (2022-2023).

                                Contexte 

Ce projet s'inscrit dans le cadre du Data Challenge Kaggle axé sur la prédiction du prix des maisons (SalePrice). L'objectif de cette étude est de développer des modèles d'apprentissage automatique de haute précision pour estimer avec justesse les prix des maisons résidentielles.

                                Mise en Œuvre 

Afin de rendre ma démarche, mes stratégies et mes résultats accessibles à tous, j'ai choisi de mettre en place cette page GitHub dédiée. Sur cette page, vous trouverez une documentation complète de mon projet, allant de la préparation des données jusqu'à l'évaluation de divers modèles de prédiction.

                                Contenu 

Vous découvrirez sur cette page :

- Description de la Stratégie : Une analyse minutieuse des choix méthodologiques opérés tout au long du projet, avec des explications claires sur les raisons qui sous-tendent chaque décision.

- Lien vers le Code : Un lien vers un dépôt GitHub contenant le code complet du projet, y compris les notebooks Jupyter pour chaque méthode explorée.

- Mémoire en Détail : Un lien vers mon mémoire complet, offrant une plongée approfondie dans chaque étape du processus, y compris la préparation des données et la mise en place des méthodes classiques.
- Données et Résultats : Des liens vous permettant d'accéder aux ensembles de données d'apprentissage et de test, ainsi qu'aux résultats de prédiction générés par mon modèle final.

                               Engagement 

Je prends l'engagement de maintenir cette page constamment à jour, afin de garantir qu'elle demeure une source d'informations actuelle et pertinente. Mon objectif est de soutenir tant les participants au défi que ceux qui aspirent à approfondir leurs compétences en analyse de données. Vos commentaires, suggestions et idées sont les bienvenus pour enrichir cette ressource et la rendre encore plus utile.

                               Remerciements 

J'exprime ma profonde gratitude envers mes enseignants qui ont rendu cette aventure captivante possible. Je suis également ouvert à vos commentaires, suggestions et discussions, que vous pouvez me faire parvenir à l'adresse suivante : mbenguegalaye26@gmail.com.

Cordialement,

Galaye Mbengue


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

- [Lien vers le Mémoire](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/M%C3%A9moire/M%C3%A9moire%20SalePrice%20Mbengue%20Galaye.pdf)<br>  Vous pouvez accéder au mémoire complet de cette étude.
- [Lien vers le Code](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/Codes/Projet_SalePrice%20(4).html)<br>
- [Lien vers les Données d'Entraînement](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/train/train.csv)<br>  Les données utilisées pour l'apprentissage des modèles.
- [Lien vers les Données de Test](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/test/test.csv)<br>  Les données utilisées pour tester les performances des modèles.
- Vous trouverez également un lien vers les données de soumission (sample_submission) fournies dans le cadre du défi. Ces données vous donneront un aperçu des attentes de format pour les prédictions finales à soumettre :
 [sample-submission](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/sample_submission/sample_submission.csv)<br>
  
Les résultats de nos tests sont disponibles dans le dossier 'submission' de ce dépôt. Vous pouvez accéder aux fichiers de résultats en suivant ce lien : 
[Lien vers les Résultats de Prédiction (submission)](https://github.com/Mbenguegalaye/Projet-SalePrice/blob/main/submission/submission.csv)<br>



https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/team

