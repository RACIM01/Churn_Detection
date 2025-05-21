# 📊 Prédiction du Churn Clients avec le Machine Learning

## 🔍 Objectif du projet

L'objectif principal de ce projet est de prédire si un client va **résilier son abonnement (churn)** ou non, en utilisant des techniques de Machine Learning. Cette prédiction permet aux entreprises de mieux comprendre leurs clients et d'agir en amont pour réduire la perte de clients.

---

## 🧰 Outils et technologies

- Python
- Pandas, NumPy pour la manipulation des données
- Matplotlib, Seaborn pour la visualisation
- Scikit-learn pour les modèles de Machine Learning
- XGBoost pour le gradient boosting
- Jupyter Notebook pour le développement

---

## 🗃️ Données

Le dataset utilisé contient des informations sur les clients (âge, type de contrat, services souscrits, moyens de paiement, etc.), ainsi qu’une variable cible appelée `Churn` qui indique si le client a résilié son abonnement.

---

## ⚙️ Étapes du projet

1. **Analyse exploratoire**
   - Visualisation des distributions des variables
   - Analyse de la corrélation entre les variables

2. **Prétraitement des données**
   - Traitement des valeurs manquantes
   - Encodage des variables qualitatives
   - Standardisation des variables numériques

3. **Modélisation**
   - Entraînement de plusieurs modèles :
     - Logistic Regression
     - KNN
     - Decision Tree
     - Random Forest
     - SVM
     - Naive Bayes
     - MLPClassifier
     - XGBoost
   - Évaluation via :
     - Accuracy
     - Precision
     - Recall
     - F1-score
     - ROC AUC

4. **Comparaison des performances**
   - Tableau et graphique comparatif des scores
   - Analyse des matrices de confusion
   - Sélection du meilleur modèle selon la métrique **Recall** (Naive Bayes)

---

## 🧠 Résultats

Le modèle **Naive Bayes** a obtenu les meilleurs résultats pour détecter les clients churn, avec un **Recall supérieur à 70%**, ce qui est crucial pour bien identifier les clients à risque de résiliation.

---

## 📁 Structure du projet

```bash
churn-prediction-project/
├── data/
│   └── telco_churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── images/
│   └── visualizations, confusion_matrices, etc.
├── README.md
└── requirements.txt
```

## ✅ À venir

Interface Web simple pour tester le modèle

Dashboard interactif (Streamlit ou Dash)

## 📬 Contact
Projet réalisé dans le cadre d’un travail universitaire en M1.
Auteur : CHAIBI Racim  
Email : chaibi.racim.pro@gmail.com
