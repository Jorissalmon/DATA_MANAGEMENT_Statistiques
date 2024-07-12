# Projet de Statistique : Analyse des Données de l'INSEE et des Collèges
## Description
Ce projet de statistique vise à explorer et analyser différentes données afin de répondre à des questions spécifiques. Il comprend deux principales analyses :

### Régression Logistique sur les Données de l'INSEE

#### Objectif : Identifier les caractéristiques influençant la probabilité qu'une femme dans un couple gagne plus que son mari.
#### Données : Les données proviennent de l'Institut national de la statistique et des études économiques (INSEE).
#### Méthodologie : Utilisation de la régression logistique pour modéliser et analyser les variables explicatives.

### Tests d'Hypothèses sur les Données de Collèges (2019-2022)

#### Objectif : Effectuer des tests d'hypothèses pour analyser les données des collèges entre 2019 et 2022.
#### Données : Les données incluent diverses métriques éducatives et administratives des collèges sur la période indiquée.
#### Méthodologie : Application de différents tests d'hypothèses pour examiner les tendances et les différences significatives.

## Structure du Projet
### data/ : Contient les jeux de données utilisés pour les analyses.
### notebooks/ : Contient les Jupyter Notebooks avec les analyses détaillées.
### scripts/ : Contient les scripts Python pour le traitement des données et les analyses.
### results/ : Contient les résultats des analyses, y compris les visualisations et les rapports.
README.md : Ce fichier, fournissant une vue d'ensemble du projet.

## Installation
Pour exécuter ce projet, vous aurez besoin d'installer les dépendances nécessaires. Utilisez l'environnement virtuel pour gérer les dépendances :

### Créez et activez un environnement virtuel :
python -m venv env
source env/bin/activate  # Sur macOS/Linux
 | env\Scripts\activate  # Sur Windows

### Installez les dépendances :
pip install -r requirements.txt

## Utilisation
### Régression Logistique sur les Données de l'INSEE

#### Préparation des données :
Assurez-vous que les données de l'INSEE sont présentes dans le répertoire data/.
Exécutez le notebook notebooks/Regression_Logistique_INSEE_Finale_v4.ipynb pour réaliser l'analyse.

#### Analyse et résultats :
Le notebook contient les étapes de préparation des données, la modélisation avec la régression logistique, et l'interprétation des résultats.

## Tests d'Hypothèses sur les Données de Collèges

### Préparation des données :
Assurez-vous que les données des collèges sont présentes dans le répertoire data/.
Exécutez le notebook notebooks/Projet_Stat_College.ipynb pour réaliser les tests d'hypothèses.
### Analyse et résultats :
Le notebook détaille les tests effectués, les hypothèses posées, et les conclusions tirées des analyses.

## Contributeurs
Joris Salmon - Data Scientist / Strategy
Nolwenn Chapellon - Data Scientist
Zakaria Camara - Data Analyst

Ce projet est soumis à l'accord de ses créateurs pour sa réutilisation

## Remerciements
Merci à l'INSEE pour la fourniture des données.
Merci aux établissements éducatifs pour les données des collèges.
