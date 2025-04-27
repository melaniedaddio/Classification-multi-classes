# Classification-multi-classes (Kaggle Compétition)

## Description
Développement d'un modèle de machine learning pour prédire la probabilité des statuts de patients (vivant, transplanté, décédé) à partir de données médicales. Utilisation d’algorithmes de classification et optimisation basée sur l'opposé de la log-vraisemblance. Prétraitement des données, feature engineering et évaluation des performances du modèle pour améliorer la précision des prédictions.

## Données
- Données issues d'une compétition Kaggle.
- Contient des informations médicales sur les patients et leurs statuts (vivant, transplanté, décédé).
- Après traitement, deux fichiers principaux sont générés : `train_df_clean.csv` et `test_df_clean.csv`.

## Utilisation
Les principaux notebooks du projet :

- **`projet_classification_cirrhosis_modele.ipynb`** : Notebook principal qui présente le modèle final retenu avec les encodages, normalisations et traitements des valeurs manquantes les plus performants.
- **`EDA.ipynb`** : Notebook d'analyse exploratoire des données (hors valeurs manquantes et normalisation), qui permet de générer les fichiers `train_df_clean.csv` et `test_df_clean.csv`.
- **`Projet.ipynb`** : Présentation des recherches, idées et décisions prises avant d’aboutir au modèle final. Ce notebook sert de documentation et n’a pas besoin d’être exécuté.
- **`reseau_neuronne.ipynb`** : Implémentation d’un réseau de neurones à titre expérimental. Bien que nos autres modèles soient plus performants pour ce cas d’usage, ce notebook a été réalisé pour l’entraînement et la pratique.

## Résultats
- Comparaison de plusieurs modèles de classification.
- Optimisation des hyperparamètres (Optuna et Gridsearch) et sélection du meilleur modèle (XGBoost) minimisant le score.

## Organisation du projet
```
classification-multi-classes/
│── projet_classification_cirrhosis_modele.ipynb/       # Notebook principal qui présente le modèle final retenu avec les encodages, normalisations et traitements des valeurs manquantes les plus performants.
│── EDA.ipynb/                                          # Notebook d'analyse exploratoire des données (hors valeurs manquantes et normalisation), qui permet de générer les fichiers `train_df_clean.csv` et `test_df_clean.csv`.
│── Projet.ipynb/                                       # Présentation des recherches, idées et décisions prises avant d’aboutir au modèle final. Ce notebook sert de documentation et n’a pas besoin d’être exécuté.
│── reseau_neuronne.ipynb/                              # Implémentation d’un réseau de neurones à titre expérimental. Bien que nos autres modèles soient plus performants pour ce cas d’usage, ce notebook a été réalisé pour l’entraînement et la pratique.
│── README.md                                           # Documentation
```

