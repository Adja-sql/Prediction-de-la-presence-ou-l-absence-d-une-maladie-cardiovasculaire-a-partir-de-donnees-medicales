# Prediction-de-la-presence-ou-l-absence-d-une-maladie-cardiovasculaire-a-partir-de-donnees-medicales

Ce projet propose une analyse de données médicales pour la classification et la régression autour du risque cardiovasculaire.

## Contenu

- `Classification.ipynb` : Modélisation de la variable cible `cardio` (classification)
- `Regression.ipynb` : Prédiction de la pression artérielle systolique `ap_hi` (régression)
- `cardio_train.csv` : Base de données utilisée
- `environnement.yml` : Notre environnement virtuel

## Technologies utilisées

- Python 3
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## Utilisation

Ouvrez les notebooks dans Jupyter et exécutez les cellules dans l’ordre.  
Les étapes de nettoyage, d’exploration et de modélisation sont expliquées dans chaque notebook.

## Résultats

- Classification : Les résultats sont assez satisfaisants, on a des AUC allant de 0.74 à 0.80 pour l'ensemble des modèles de classification.
- Régression : Les résultats ne sont pas bons étant donné que notre variable à prédire (`ap_hi` ou pression artérielle systolique) n'était pas possible à partir des autres variables (elles ne sont pas adaptées malheureusement).

