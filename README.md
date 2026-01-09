# Mini-Projet : Régression Linéaire et Régression Logistique

**Master 1 Intelligence Artificielle (M1 IA)**

---

## 📌 Objectif du projet

Ce mini-projet a pour objectif de consolider les bases de l’apprentissage supervisé à travers l’implémentation et l’analyse de deux modèles fondamentaux :

* **Régression Linéaire** pour la prédiction de variables continues
* **Régression Logistique** pour les problèmes de classification binaire

---

## 📂 Contenu du repository

* `mini_projet_ML_RLineair.ipynb`
  Implémentation complète de la **régression linéaire** sur un jeu de données réel.

* `mini_projet_ML_Rlogistique.ipynb`
  Implémentation de la **régression logistique** appliquée au dataset **Iris** (classification binaire).

* `MiniProjetML2026.pdf`
  Sujet officiel du mini-projet.

---

## 🧠 Partie 1 : Régression Linéaire

### ✔ Données

Un jeu de données de régression avec une variable cible numérique.

### ✔ Étapes réalisées

* Analyse des corrélations à l’aide d’une **heatmap**
* Formalisation du modèle :
  **y = β₀ + Σ βᵢxᵢ + ε**
* Entraînement du modèle
* Évaluation des performances avec :

  * **R² (Coefficient de détermination)**
  * **MSE (Erreur quadratique moyenne)**
* Interprétation des coefficients pour analyser l’importance des variables

---

## 🧠 Partie 2 : Régression Logistique

### ✔ Données

Dataset **Iris** (scikit-learn), transformé en **classification binaire**.

### ✔ Étapes réalisées

* Préparation et normalisation des données

* Modélisation de la probabilité via la fonction sigmoïde :

  [
  P(y=1|x) = \frac{1}{1 + e^{-z}}
  ]

* Entraînement du modèle

* Évaluation à l’aide de :

  * **Matrice de confusion**
  * **Accuracy**
  * **Précision**
  * **Recall**

---

## 🛠️ Technologies utilisées

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn
* Google Colab

---

## 👤 Auteur

**Mohamed Mahmoud Said**
**Matricule : C34666**
Master 1 Intelligence Artificielle
Année universitaire 2025–2026

