# 🔍 Détection de Fraude sur les Cartes Bancaires par Machine Learning

Ce projet de PFE vise à développer un modèle de détection des transactions frauduleuses à l'aide d'algorithmes de machine learning. Il s'appuie sur des données enrichies et des critères complexes comme la distance géographique, les MCC à risque, les transactions nocturnes, et l’historique comportemental de la carte.

---

## 📁 Structure du projet

```bash
.
├── data/
│   └── code_generation_dataset_final.csv     # Dataset final enrichi
├── model/
│   └── fraud_detection_model_rf_final.pkl    # Modèle Random Forest entraîné
├── notebooks/
│   ├── fraud_model_and_gradio_full.ipynb     # Entraînement + Gradio interface
│   └── visualisations_tables_croisees.ipynb  # Visualisation des analyses croisées
└── README.md


🧠 Objectifs
Générer une dataset simulée riche en comportements frauduleux réalistes

Détecter des schémas de fraude géographique, temporelle ou comportementale

Implémenter un modèle interprétable basé sur Random Forest

Déployer une interface de test interactive avec Gradio



🔧 Technologies utilisées
Python 3.x

Pandas / NumPy

Scikit-Learn

Matplotlib / Seaborn

Gradio (interface web)




📊 Dataset
Le dataset est entièrement simulé et comprend :

Des transactions normales et frauduleuses

Des critères de fraude : tentatives refusées, MCC à risque, distance géographique impossible, horaires suspects, etc.

Des indicateurs temporels : heure, jour, weekday

Des flags comme IS_NIGHT, IS_GEOLOGICALLY_IMPOSSIBLE, CASE_AFTER_EXPIRY...
