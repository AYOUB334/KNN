# KNN
Ce projet contient une implémentation de l'algorithme **K-Nearest Neighbors (KNN)** avec une pondération basée sur la **distance (TDKNN)**. L'algorithme est appliqué sur un petit dataset pour illustrer les étapes de classification.

## 🧠 Objectifs pédagogiques

- Implémenter un algorithme KNN simple
- Ajouter une **pondération par distance** (plus un voisin est proche, plus il pèse lourd)
- Analyser les distances euclidiennes et leurs implications
- Visualiser les étapes du vote pondéré

## 🗂️ Contenu

- `Exercice7-TDKNN.ipynb` : Notebook Jupyter contenant :
  - Le jeu de données
  - Le calcul des distances
  - Le classement des voisins
  - Le vote pondéré
  - L'identification de la classe la plus probable

## 🔧 Dépendances

- Python 3.x
- `numpy`
- `pandas`
- `matplotlib` (optionnel, pour les visualisations)

Tu peux les installer avec :

```bash
pip install numpy pandas matplotlib
