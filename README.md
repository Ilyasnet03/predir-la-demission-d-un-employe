# predir-la-demission-d-un-employe
application pour prédire si un employé va démissionner ou pas .
🏢 IA de Prédiction des Démissions (RH Analytics)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-green.svg)
![Interface](https://img.shields.io/badge/UI-Gradio-orange.svg)

## 📝 Description du projet
Ce projet utilise le **Machine Learning** pour aider les départements RH à identifier les employés risquant de quitter l'entreprise. En analysant des données historiques (satisfaction, charge de travail, salaire, évaluation), l'IA prédit la probabilité de démission et identifie les facteurs d'influence majeurs.

## 🚀 Fonctionnalités
- **Nettoyage automatique** des données (doublons, valeurs manquantes, outliers).
- **Analyse prédictive** via l'algorithme Random Forest.
- **Visualisation des données** (Importance des critères, Matrice de confusion, Corrélations).
- **Interface Web interactive** avec Gradio pour tester des profils d'employés en temps réel.

## 📊 Critères analysés
Le modèle se base sur les facteurs suivants (classés par importance) :
1. **Satisfaction** (Indicateur n°1 du moral)
2. **Dernière Évaluation** (Note de performance)
3. **Heures Mensuelles** (Charge de travail)
4. **Ancienneté**
5. **Nombre de Projets**
6. **Niveau de Salaire**
