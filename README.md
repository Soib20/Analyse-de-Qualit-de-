# Analyse-de-Qualit-de-
Analyse d’un an de données de qualité de l’air issues de capteurs chimiques MOS, incluant EDA, analyse temporelle, modélisation prédictive des polluants (CO, NOx, NO₂, benzène) et comparaison avec un analyseur certifié.
<p align="center">
  <img src="https://raw.githubusercontent.com/pandas-dev/pandas/main/web/pandas/static/img/pandas.svg" width="18%">
</p>

<h1 align="center">🌫️ Air Quality Analysis — Capteurs chimiques & Polluants atmosphériques</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas">
  <img src="https://img.shields.io/badge/Scikit--learn-ML-green?logo=scikitlearn">
  <img src="https://img.shields.io/badge/Time%20Series-Analysis-lightgrey">
  <img src="https://img.shields.io/badge/Environmental%20Data-Air%20Quality-brightgreen">
</p>

---

## 📑 Table des matières
- [Description du dataset](#-description-du-dataset)
- [Objectifs du projet](#-objectifs-du-projet)
- [Structure du dépôt](#-structure-du-dépôt)
- [Analyse exploratoire (EDA)](#-1-analyse-exploratoire-eda)
- [Analyse temporelle](#-2-analyse-temporelle)
- [Modélisation](#-3-modélisation)
- [Interprétation des résultats](#-4-interprétation-des-résultats)
- [Rapport final](#-rapport-final)
- [Reproductibilité](#-reproductibilité)
- [Auteur](#-auteur)

---

## 🧪 Description du dataset

Le jeu de données contient **9358 enregistrements horaires** provenant d’un dispositif multisensoriel de qualité de l’air équipé de **5 capteurs chimiques en oxyde métallique**.

📍 **Localisation :** zone urbaine fortement polluée en Italie  
📅 **Période :** mars 2004 → février 2005 (1 an complet)  
📡 **Capteurs :** 5 capteurs MOS (Metal Oxide Sensors)  
🧭 **Polluants mesurés :**
- CO (monoxyde de carbone)  
- NMHC (hydrocarbures non méthaniques)  
- Benzène  
- NOx (oxydes d’azote totaux)  
- NO2 (dioxyde d’azote)  

Les valeurs de référence proviennent d’un **analyseur certifié colocalisé**, ce qui permet d’évaluer la performance des capteurs chimiques.

---

## 🎯 Objectifs du projet

- Étudier les variations temporelles des polluants atmosphériques.  
- Analyser les réponses des capteurs chimiques MOS.  
- Identifier les relations entre capteurs et polluants.  
- Détecter des patterns saisonniers, hebdomadaires et journaliers.  
- Construire des modèles prédictifs pour estimer les concentrations de polluants.  
- Évaluer la capacité des capteurs à remplacer un analyseur certifié.  

---

## 📂 Structure du dépôt

---

## 🔍 1. Analyse exploratoire (EDA)

- Statistiques descriptives  
- Analyse des capteurs MOS  
- Corrélations capteurs ↔ polluants  
- Visualisations multi-variables  
- Détection des valeurs aberrantes  
- Analyse des conditions environnementales  

---

## ⏳ 2. Analyse temporelle

- Tendances annuelles  
- Variations saisonnières  
- Cycles hebdomadaires  
- Cycles journaliers (trafic routier, météo…)  
- Séries temporelles multi-capteurs  

---

## 🤖 3. Modélisation

Modèles testés :
- Régressions linéaires  
- RandomForestRegressor  
- GradientBoosting  
- XGBoost  
- Modèles temporels (selon besoin)

Évaluation :
- RMSE  
- MAE  
- R²  
- Comparaison capteurs vs analyseur certifié  

---

## 🧠 4. Interprétation des résultats

- Importance des features  
- SHAP values  
- Analyse des capteurs les plus fiables  
- Discussion sur la qualité de l’air locale  

---

## 📄 Rapport final

Le rapport complet est disponible dans `report/`.  
Il contient :
- Méthodologie  
- Résultats  
- Visualisations  
- Interprétation  
- Conclusion  

---

## 🚀 Reproductibilité

1. Cloner le dépôt  
2. Installer les dépendances  
3. Exécuter le notebook  

---

## ✨ Auteur

Projet réalisé par **Mlooi**, dans le cadre d’une analyse approfondie de données environnementales.

