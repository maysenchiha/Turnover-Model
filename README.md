# 📊 Prédiction du Turnover des Employés

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--learn-orange.svg)

## 📝 Description

Ce projet de machine learning vise à développer un modèle prédictif permettant d'anticiper le risque de départ des employés au sein d'une organisation. 
En analysant différents facteurs RH (satisfaction, évaluation, charge de travail, ancienneté, etc.), le système identifie les employés susceptibles de quitter 
l'entreprise et aide à mettre en place des stratégies de rétention efficaces.

## 🎯 Objectifs

- **Prédire le turnover** : Identifier les employés à risque de démission avec un haut niveau de précision
- **Analyser les facteurs clés** : Comprendre les variables influençant la décision de départ
- **Optimiser la rétention** : Fournir des insights actionnables pour améliorer la fidélisation des talents
- **Réduire les coûts** : Minimiser les coûts liés au recrutement, à la formation et à la perte de productivité
- **Support décisionnel** : Aider les RH à prendre des décisions basées sur les données

## 📁 Structure du Projet
├── Prediction de Sortie des employées.ipynb  # Modèle principal de prédiction                                                                                                                                          
├── data generation_Final.ipynb                # Génération et préparation des données                                                                                                                                  
└── turnover_dataset.csv                       # Dataset des employés
## Fichiers détaillés

- **`Prediction de Sortie des employées.ipynb`** 
  - Analyse exploratoire des données (EDA)
  - Visualisation des tendances et corrélations
  - Prétraitement et feature engineering
  - Entraînement de différents modèles de classification
  - Évaluation des performances (accuracy, precision, recall, F1-score)
  - Interprétation des résultats et importance des features

- **`data generation_Final.ipynb`** 
  - Génération de données synthétiques (si applicable)
  - Nettoyage et transformation des données
  - Gestion des valeurs manquantes
  - Équilibrage des classes
  - Export du dataset final

- **`turnover_dataset.csv`** 
  - Dataset contenant les informations sur les employés
  - Variables typiques : satisfaction, évaluation, nombre de projets, heures moyennes, ancienneté, accidents de travail, promotions, département, salaire, etc.

## 🛠️ Technologies Utilisées

- **Python 3.x**
- **Pandas & NumPy** - Manipulation et analyse de données
- **Scikit-learn** - Modélisation et machine learning
- **Matplotlib & Seaborn** - Visualisation de données
- **Jupyter Notebook** - Environnement de développement interactif
- **XGBoost / Random Forest** - Algorithmes de classification (selon implémentation)
