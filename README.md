# TP1 - Apprentissage Supervisé

Ce projet contient deux exercices pratiques d'apprentissage supervisé :

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

## Prérequis et installation

Pour exécuter les scripts, installez les dépendances nécessaires :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Exécution

```bash
python3 exercice1.python
python3 exercice2.python
```
