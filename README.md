# WC2026 Winner Prediction – Logistic Regression

## 🇫🇷 Prediction Coupe du Monde 2026 – Régression Logistique

## 📌 Description du projet

Ce projet a pour objectif de construire un modèle de Machine Learning capable d’estimer les probabilités de victoire des équipes participantes à la Coupe du Monde 2026.

Nous utilisons une approche basée sur la **régression logistique**, un algorithme simple et interprétable de classification probabiliste.

L’objectif n’est pas de prédire avec certitude le vainqueur, mais de **simuler des probabilités de victoire pour chaque équipe** à partir de données historiques de matchs internationaux.

---

## 🧠 Concept principal

Le modèle apprend à partir de matchs passés en utilisant des caractéristiques (features) comme :

- Différence de classement FIFA
- Différence de buts moyens par match
- Forme récente des équipes
- Statistiques offensives et défensives

Ensuite, il prédit la probabilité de résultat d’un match :

- Victoire équipe A
- Match nul
- Victoire équipe B

---

## ⚙️ Méthodologie

1. Collecte de données de matchs internationaux
2. Nettoyage et transformation des données
3. Création de features (différences entre équipes)
4. Entraînement d’un modèle de régression logistique
5. Prédiction des probabilités de chaque match
6. Simulation de la Coupe du Monde (Monte Carlo)
7. Estimation des chances de victoire finale de chaque équipe

---

## 🛠️ Technologies utilisées

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle dataset / Football API

---

## 🎯 Objectif final

Obtenir une estimation du type :

- France : 17%
- Brésil : 15%
- Argentine : 13%
- Angleterre : 11%

---

## 🚀 Améliorations possibles

- Utilisation de modèles plus avancés (Random Forest, XGBoost)
- Ajout du système Elo rating
- Simulation complète des phases de groupe et élimination directe
- Intégration d’une interface web (Next.js)

---





---

# 🇬🇧 2026 World Cup Winner Prediction – Logistic Regression

## 📌 Project Description

This project aims to build a Machine Learning model that estimates the winning probabilities of teams participating in the 2026 FIFA World Cup.

We use a **Logistic Regression model**, a simple and interpretable probabilistic classification algorithm.

The goal is not to predict the exact winner, but to **estimate winning probabilities for each team** based on historical international match data.

---

## 🧠 Core Concept

The model learns from past matches using features such as:

- FIFA ranking difference
- Average goals difference per match
- Recent team performance
- Offensive and defensive statistics

It then predicts the probability of match outcomes:

- Team A win
- Draw
- Team B win

---

## ⚙️ Methodology

1. Collect international match data
2. Clean and preprocess the dataset
3. Feature engineering (team differences)
4. Train a Logistic Regression model
5. Predict match outcome probabilities
6. Simulate the World Cup (Monte Carlo simulation)
7. Estimate each team’s probability of winning the tournament

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle dataset / Football API

---

## 🎯 Final Goal

Produce a probability distribution such as:

- France: 17%
- Brazil: 15%
- Argentina: 13%
- England: 11%

---

## 🚀 Possible Improvements

- Use advanced models (Random Forest, XGBoost)
- Add Elo rating system
- Full tournament simulation (group stage + knockout)
- Build a web interface (Next.js)
