# Mod-le-de-pr-visions-de-trafic-passagers
Description du projet
Ce projet vise à développer un modèle d'apprentissage machine pour la prévision du trafic passagers dans les principaux aéroports de la concession État du Cameroun/ADC S.A. L'objectif est de fournir des projections fiables sur un horizon de 5 ans, afin d'optimiser la gestion des ressources aéroportuaires, d'améliorer la prise de décision opérationnelle et d'affiner la planification budgétaire.
Objectifs principaux
Prévision du trafic passagers trimestriel : Projection du trafic trimestriel des passagers des aéroports de la concession aéroportuaires de 2025 à 2029.
Gestion des ressources : Faciliter la planification opérationnelle, budgétaire et stratégique.
Mise en production : Déployer un modèle robuste prêt à l’emploi dans un environnement opérationnel.
Méthodologie
1. Collecte et préparation des données
Données trimestrielles sur le trafic passagers (2016-2024).
Traitement des valeurs manquantes et des anomalies dues à des événements externes (ex. pandémie de Covid-19 en 2020).
2. Modélisation
Exploration des modèles d’apprentissage machine adaptés aux petits jeux de données (36 observations).
Analyse comparative entre des approches traditionnelles (ARIMA, SARIMA) et des modèles bayésiens.
3. Validation et évaluation
Tests sur des données historiques et prédictions comparées avec des données réelles.
Utilisation de métriques comme le RMSE et le MAPE pour évaluer la performance.
4. Mise en production
Développement d’un tableau de bord interactif via Power BI pour visualiser les prévisions.
Technologies utilisées
Langages : Python (pandas, numpy scikit-learn, statsmodels)
Outils de visualisation : Matplotlib
Gestion des données : Excel pour les bases de données aéroportuaires
5. Résultats attendus
Modèle prévisionnel opérationnel pour un horizon de 5 ans.
Tableau de bord Power BI pour visualiser les prévisions de trafic passagers.
Rapport détaillé sur les tendances du trafic aérien et recommandations stratégiques.
6. Défis rencontrés
Données manquantes : Trafic de certaines années marquées par des anomalies (ex. Les trimestres 2 et 3 des années 2020 qui ont été marqués par le Covid-19).
Taille limitée du dataset : Adaptation des modèles à des échantillons réduits (36 observations).
Absence de certaines données historiques sous forme trimestrielles pour un des prédicteurs : Utilisation de l'interpolation linéaire pour passer des données annuelles aux données trimestrielles.
Comment exécuter le projet
7. Cloner le dépôt :
bash
Copy code
git clone https://github.com/Emerybabodo/Trafic-passengers-forecast-of-Cameroon-Airports
cd Trafic-passengers-forecast-of-Cameroon-Airports
8. Installer les dépendances :
bash
Copy code
pip install -r requirements.txt
9. Exécuter les notebooks :
Ouvrir et exécuter les notebooks dans scripts/ pour visualiser les étapes de collecte, de modélisation et d’évaluation des données.

Auteur
Christian-Jacques BABODO- Chargé d'études Innovation digitale, Aviation Data Scientist.

Contact
📧 Email : emerybabodo@gmail.com
🔗 LinkedIn : www.linkedin.com/in/christian-jacques-babodo-emerybabodo
