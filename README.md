# TP1 & Mini-Projet - Apprentissage Supervisé

Ce projet contient les exercices pratiques et le mini-projet d'apprentissage supervisé :

## 1. Exercice 1 : Prédiction du tarif des courses Uber (Régression)
- **Fichier :** `exercice1.python`
- **Jeu de données :** `uber.csv`
- **Modèles utilisés :** 
  - Régression Linéaire (`LinearRegression`)
  - Forêt Aléatoire (`RandomForestRegressor`)
- **Métriques d'évaluation :** MAE, RMSE, R²
- **Visualisation :** Graphique des valeurs réelles vs valeurs prédites.

## 2. Exercice 2 : Prédiction de survie - Titanic (Classification)
- **Fichier :** `exercice2.python`
- **Jeu de données :** `train.csv`
- **Modèles utilisés :**
  - Régression Logistique (`LogisticRegression`)
  - Forêt Aléatoire (`RandomForestClassifier`)
- **Métriques d'évaluation :** Accuracy, Rapport de classification (Precision, Recall, F1-Score), Matrice de confusion.
- **Visualisation :** Heatmap de la matrice de confusion (`seaborn`).

## 3. Mini-Projet : Prédiction des Maladies Cardiovasculaires
- **Fichier :** `mini_projet_ml.ipynb`
- **Jeux de données :** `heart.csv`, `heartdiseases.csv`
- **Tâche :** Classification binaire (Détection de cardiopathie)
- **Modèles comparés :** Régression Logistique, KNN, SVM, Random Forest, Gradient Boosting
- **Méthodologie :**
  - Analyse exploratoire (EDA) et prétraitement (One-Hot Encoding, StandardScaler)
  - Validation croisée stratifiée 5-folds (`StratifiedKFold`)
  - Optimisation des hyperparamètres (`GridSearchCV`)
  - Évaluation approfondie : Matrices de confusion, courbes ROC-AUC, Feature Importance

## Prérequis et installation

Pour exécuter les scripts et notebooks, installez les dépendances nécessaires :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Exécution

```bash
python3 exercice1.python
python3 exercice2.python
jupyter notebook mini_projet_ml.ipynb
```
