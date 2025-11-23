# TP Série 2 – Optimisation II  
## Université de Yaoundé I — Département d’Informatique  
**INF4127 : Optimisation II – Année académique 2025-2026**  
**Date limite : 23 Novembre 2025 à 20h**

---

## Objectif du TP
Ce TP consiste à reprendre les expérimentations du *Chapitre 2 : Optimisation numérique sans contraintes* (pages 32 à 34 du support de cours), puis à appliquer exactement les mêmes techniques à 04 fonctions d’optimisation :

1. **Fonction du support de cour**  
   \( f(x, y) = (1/2)(x)^2 + (7/2)(y)^2 \)

2. **Fonction de Rosenbrock**  
   \( f(x, y) = (1-x)^2 + 100(y - x^2)^2 \)

3. **Fonction quadratique**  
   \( f(x, y) = x^2 - y^2 \)

4. **Fonction de Himmelblau**  
   \( f(x, y) = (x^2 + y - 11)^2 + (x + y^2 - 7)^2 \)

Le but est d’étudier le comportement des algorithmes d’optimisation vus en cours sur des fonctions.

---

## Contenu attendu

Pour **chaque fonction**, produire un **notebook Jupyter complet**, contenant :

- L’implémentation de la fonction  
- Son gradient (si nécessaire)  
- L’application d’un ou plusieurs algorithmes vus en cours :  
  - descente de gradient  
  - descente de gradient avec pas optimal    
- Des visualisations :  
  - surface 3D  
  - trajectoire de l’algorithme  
- Une analyse détaillée :  
  - comportement de la convergence  
  - rôle du point initial  
  - vitesse de convergence  
  - difficultés

---

## 🗂 Organisation du dépôt GitHub

│
├── README.md
├── TP_OptimisationNumeriqueSansContraintes.ipynb
└── requirements.txt(Les dependances utilises)
