# Décomposition QR en Python

Ce projet présente une implémentation simple et pédagogique de la **décomposition QR** d'une matrice, réalisée en Python à l'aide de NumPy et Jupyter Notebook.

## Objectif

L’objectif est de comprendre et d’illustrer la **décomposition QR**, une méthode fondamentale en algèbre linéaire utilisée notamment pour la résolution de systèmes linéaires et les calculs de valeurs propres.

Le projet comprend :
- Une partie théorique
- Une **implémentation manuelle** de la décomposition QR par la méthode de Gram-Schmidt.
- Une **comparaison avec la fonction `numpy.linalg.qr`**.
- Une Applicationaà la résolution d'un système linéaire

## Rappels mathématiques

Pour toute matrice $A \in \mathbb{R}^{m \times n}$, la décomposition QR consiste à écrire :

$$
A = Q \times R
$$

où :
- $Q$ est une matrice orthogonale ($Q^T Q = I$)
- $R$ est une matrice triangulaire supérieure.

Cette factorisation est très utilisée en calcul scientifique pour :
- Résoudre des systèmes linéaires,
- Effectuer des régressions linéaires,
- Calculer des valeurs/vecteurs propres.

## Technologies utilisées

- **Python 3**
- **NumPy**
- **Jupyter Notebook**
