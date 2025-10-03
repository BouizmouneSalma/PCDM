# 🧠 Prédiction des Charges Médicales avec l’IA

## 📌 Contexte
L’objectif est de mettre en place un **système intelligent** capable d’estimer de manière précise les **charges médicales** que chaque assuré devra payer.  

🔹 Cette solution vise à :  
- Anticiper les coûts médicaux.  
- Améliorer la **transparence** pour les assurés.  
- Aider l’entreprise à optimiser ses **politiques tarifaires**.  

---

## 📊 Jeu de Données
Les données utilisées proviennent des dossiers médicaux et contiennent les variables suivantes :  

- `Age` : Âge de l’assuré  
- `Sex` : Sexe  
- `BMI` : Indice de masse corporelle  
- `Children` : Nombre d’enfants à charge  
- `Smoker` : Habitude tabagique (oui/non)  
- `Region` : Région géographique  
- `Charges` : Charges médicales à prédire (valeur cible)  

---

## 🚀 Fonctionnalités principales

### 📝 Feature Story 1 : Analyse et Préparation des Données
- Chargement et exploration du dataset.  
- Analyse descriptive et visualisations (📈 histogrammes, heatmaps, pairplots).  
- Traitement des valeurs manquantes et doublons.  
- Détection et gestion des outliers (z-score, IQR).  
- Encodage des variables catégoriques et normalisation des variables numériques.  

### 🤖 Feature Story 2 : Entraînement des Modèles
- Régression Linéaire.  
- Random Forest.  
- XGBoost.  
- Support Vector Regressor (SVR).  
- Pipelines Scikit-learn intégrant prétraitement + entraînement.  

### ⚙️ Feature Story 3 : Optimisation
- GridSearchCV & RandomizedSearchCV avec validation croisée.  
- Optimisation des hyperparamètres (Random Forest, XGBoost).  

### 📈 Feature Story 4 : Évaluation
- Visualisation des performances (graphiques de résidus, prédictions vs. valeurs réelles).  
- Comparaison des modèles via RMSE, MAE et R².  

### 💾 Feature Story 5 : Déploiement
- Exportation du modèle final avec `joblib`.  
- Interface utilisateur simple : saisie des informations d’un assuré ➝ estimation des charges.  

### 📚 Feature Story 6 : Documentation
- Code commenté (Markdown dans notebook).  
- README structuré (vous êtes en train de le lire ✨).  

---

## 🛠️ Technologies Utilisées
- **Python** 🐍  
- **Pandas / NumPy** : manipulation des données  
- **Matplotlib / Seaborn** : visualisations  
- **Scikit-learn** : prétraitement, modèles, optimisation  
- **XGBoost** : gradient boosting performant  
- **Joblib / Pickle** : sauvegarde du modèle  
