# 📘 INF 4127 : TPE Calcul Symbolique

## Description

Dans ce projet, nous allons présenter un problème d’optimisation inspiré d’une situation réelle simplifiée. Nous utiliserons la bibliothèque **SymPy** pour effectuer les calculs symboliques nécessaires à la résolution de ce problème.

## Problématique

- **Produits** :
  - **Produit A** : quantité \( x \)
  - **Produit B** : quantité \( y \)

- **Demande totale** :
  \[
  x + y = D
  \]

- **Coût total de production** :
  \[
  C(x,y) = a x^2 + b y^2 + c x + d y
  \]

- **Objectif** :
  - Minimiser le coût total \( C(x,y) \)
  - Sous contraintes : \( x + y = D \) et \( x, y \ge 0 \)

## Plan du Notebook

1. **Définition du problème** :
   - Présentation des produits, de la demande et du coût de production.
   - Identification des contraintes.

2. **Résolution symbolique avec SymPy** :
   - Construction du Lagrangien.
   - Calcul des dérivées partielles.
   - Résolution symbolique pour obtenir la solution générale.

3. **Instanciation numérique et solution candidate** :
   - Substitution des valeurs numériques des paramètres.
   - Extraction de la solution candidate intérieure.

4. **Vérification des solutions admissibles** :
   - Vérification de la positivité des quantités.
   - Considération des solutions frontières.

5. **Visualisation graphique des scénarios** :
   - Tracé des contours de coût.
   - Affichage de la contrainte \( x + y = D \).
   - Mise en évidence du point optimal.

6. **Analyse complémentaire (optionnelle)** :
   - Graphique comparatif des coûts.
   - Interprétation économique de la répartition optimale.

7. **Conclusion et interprétation** :
   - Résumé de la solution optimale et des coûts associés.
   - Explication de la stratégie optimale de production.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone 'https://github.com/UE-Technique-d-Optimisation-II/INF4127-TPE-Calcul-Symbolique/blob/main/README.md'

    Accédez au répertoire du projet :
    bash

cd "INF4127-TPE-Calcul-Symbolique"

Installez les dépendances :
bash

    pip install -r requirements.txt

Dépendances nécessaires

Assurez-vous d'avoir les bibliothèques suivantes installées :

    sympy
    numpy
    matplotlib

Vous pouvez les installer avec la commande suivante :
bash

pip install sympy numpy matplotlib

Utilisation

    Ouvrez le notebook Jupyter :
    bash

    jupyter notebook

    Lancez le notebook correspondant au projet.

    Exécutez les cellules une par une pour voir les résultats de l'optimisation et la visualisation graphique.
