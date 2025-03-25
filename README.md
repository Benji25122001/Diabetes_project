# Diabetes_project
Prédiction du Diabète par Régression Logistique
Description du projet
Ce projet en biostatistique utilise des modèles de régression logistique pour prédire la probabilité qu'un individu développe le diabète, en fonction de divers facteurs tels que l'âge, la pression sanguine, le taux d'insuline, le sexe, et d'autres variables démographiques et biologiques. L'objectif est de tester différents modèles de régression logistique, évaluer leur performance et identifier les variables les plus influentes dans la prédiction du diabète.

Objectif
Le but principal de ce projet est de développer plusieurs modèles de régression logistique pour prédire si un individu sera atteint de diabète ou non. En fonction des variables disponibles, plusieurs modèles seront testés et comparés afin de déterminer lequel offre la meilleure précision de prédiction.

Variables utilisées
Les principales variables utilisées pour prédire la probabilité de diabète sont :

Age : L'âge de l'individu.

Pression sanguine : La pression artérielle de l'individu.

Taux d'insuline : La quantité d'insuline dans le sang.

Sexe : Le sexe de l'individu (Homme/Femme).

IMC : L'indice de masse corporelle.

Niveaux de glucose : Le taux de glucose dans le sang.

Antécédents familiaux de diabète : Présence d'antécédents familiaux de diabète.

Autres facteurs de risque : D'autres variables selon les données disponibles.

Modèles de régression logistique
Les modèles suivants seront testés pour prédire le diabète :

Régression logistique simple : Modèle de base avec une seule variable prédictive.

Régression logistique multivariée : Modèle intégrant plusieurs facteurs simultanément.

Régression logistique avec régularisation : Modèles utilisant la régularisation L1 (lasso) ou L2 (ridge) pour éviter le sur-apprentissage.

Régression logistique avec interactions : Modèle incluant des interactions entre certaines variables pour capturer des relations non linéaires.

Méthodologie
Préparation des données :

Nettoyage des données (traitement des valeurs manquantes, encodage des variables catégorielles, normalisation des variables numériques).

Séparation des données en ensembles d'entraînement et de test (train/test split).

Construction des modèles :

Utilisation de la fonction glm() de R pour entraîner les modèles de régression logistique.

Application de la régularisation avec des bibliothèques comme glmnet pour l'implémentation de Lasso et Ridge.

Évaluation des performances :

Calcul des performances des modèles sur l'ensemble de test en utilisant des métriques telles que :

AUC-ROC : Surface sous la courbe ROC.

Précision : Proportion des classifications correctes parmi les positives.

Rappel : Proportion des vrais positifs identifiés.

F1-score : Moyenne harmonique entre la précision et le rappel.

Comparaison des modèles :

Comparaison des modèles pour identifier celui offrant la meilleure performance globale.

