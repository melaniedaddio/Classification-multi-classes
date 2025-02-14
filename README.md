# Classification-multi-classes
## Pour importer les tables propres faire 
'''
%run EDA.ipynb
'''

ou 

importer les fichiers "train_df_clean.csv" et "test_df_clean.csv"

## projet_classification_cirrhosis_modele : Notebook principal à regarder si on veut mieux comprendre comment on a construit notre score
Modèle final choisi comme etant le plus performant, avec les encodages, normalisations et traitement des valeurs manquantes les plus performantes.

## EDA.ipynb : 
Traitement et analyse des variables (hors valeurs manquantes et normalisation). Ce notebook permet de générer deux fichiers csv traités : "train_df_clean.csv" et "test_df_clean.csv", qui seront utilisés dans tous nos notebooks.

## Projet.ipynb : 
Ce notebook a pour objectif de montrer toutes les recherches, idées et décision prises avant d'aboutir à la version finale "projet_classification_cirrhosis_modele.ipynb".
Il n'est pas nécessaire de lancer les cellules, ce notebook appuie simplement les différentes idées et recherches effectuées tout le long du projet.

## reseau_neuronne.ipynb :
Ce notebook a pour objectif de mettre en place un petit reseau de neuronne.
Nous savons que nos autres modèles fait sont plus performants pour notre sujet. Mais nous avons tout de meme voulu contruire un reseau de neuronne pour pratiquer.