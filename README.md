# Projet de fin de formation en data analyse
![logo](https://brandlogovector.com/wp-content/uploads/2021/06/Bolt-Food-Logo.png)

## Contexte
Bolt est un acteur majeur des prestations de VTC dans le monde.  
Sa filiale **Bolt Food** propose la livraison de repas dans certains pays, mais pas encore en France.

## Mission
**Définir s’il existe une opportunité pour **Bolt Food** sur le marché français de la livraison de repas.**

## Objectifs
- **Analyser le marché existant.**  
- Étudier **les profils et comportements des consommateurs.**  
- Examiner **les pratiques concurrentielles.**  
- Émettre des **recommandations argumentées** pour répondre à la problématique.

## L'ensemble de l'analyse est à consulter dans le notebook du projet :
- Sur Google Colab  
  <a target="_blank" href="https://colab.research.google.com/github/cyrilgrv/bolt-food/blob/main/Bolt_Food.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" style="vertical-align: middle;"/>
  </a>

- [A télécharger sur ce repo](https://github.com/cyrilgrv/bolt-food/blob/main/Bolt_Food.ipynb)

## Plan du notebook :
- **Exploration et nettoyage**
    - Exploration du jeu de données
    - Nettoyage et optimisation
    - Temporalité du jeu de données
- **Explorations visuelles et élements d'analyse**
    - Analyse des commandes
    - Analyse par concurrent
    - Parts de marché et chiffre d'affaire
    - Panier moyens
    - Analyse de la clientèle
    - Observations des corrélations
    - Analyses géographiques
    - Analyse IdF vs reste de la France
    - Analyse des types de nourriture
    - Analyse des vendeurs
    - Analyse des promotions
    - Analyse des frais

## Sources des données

| Nom du fichier | Lien |
|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| ![CSV Lines Badge](https://img.shields.io/badge/customers%2Ecsv-378%20observations-informational)         | [Télécharger](http://cgphoto.cluster010.ovh.net/data/bolt_food/customers.csv)    |
| ![CSV Lines Badge](https://img.shields.io/badge/products%2Ecsv-1.711.616%20observations-informational)    | [Télécharger](http://cgphoto.cluster010.ovh.net/data/bolt_food/products.csv)     |
| ![CSV Lines Badge](https://img.shields.io/badge/transactions%2Ecsv-807.676%20observations-informational)  | [Télécharger](http://cgphoto.cluster010.ovh.net/data/bolt_food/transactions.csv) |

Données collectées par [Foxintelligence](https://www.foxintelligence.io/fr/accueil/)

## Temporalité du jeu de données
![Timeline](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/timeline.png)

## Outils mis en oeuvre
[![Python for Data Analysis](https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![VSCode](https://img.shields.io/badge/Editor-VSCode-blue?logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

## Librairies utilisées
[![Pandas](https://img.shields.io/badge/Pandas-2.2.3-blue)](https://github.com/pandas-dev/pandas)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.9.2-blue)](https://github.com/matplotlib/matplotlib)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-blue)](https://github.com/mwaskom/seaborn)
[![Missing Data Analysis](https://img.shields.io/badge/Missing%20Data-missingno-orange)](https://github.com/ResidentMario/missingno)
[![Progress Bars](https://img.shields.io/badge/Progress%20Bars-tqdm-yellowgreen)](https://github.com/tqdm/tqdm)
[![Text Comparison](https://img.shields.io/badge/Text%20Comparison-difflib-blueviolet)](https://github.com/python/cpython/blob/3.13/Lib/difflib.py)
[![Interactive calendar](https://img.shields.io/badge/Interactive%20Calendar-calplot-orange)](https://github.com/tomkwok/calplot)

## Présentations des recommendations et analyses détaillées
[![Presentation PDF](https://img.shields.io/badge/Voir%20la%20présentation-PDF-red)](https://github.com/cyrilgrv/bolt-food/blob/aa5aea033030de06a1f90606a2d7b6beef4d6bdc/Projet_Bolt-Food_Presentation.pdf)

## Quelques exemples d'analyses graphiques effectuées en Python
### Répartition des commandes dans le temps et par concurrent
![Concurrents](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/competitors.png)

### Chiffre d'affaires par concurrent et par région française
![CA](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/ca.png)

### Répartition des commandes dans la journée
![Heures](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/hours.png)

### Evolution des frais dans le temps
![Frais](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/fees.png)

### Commandes en promotion par mois et par concurrent
![Promo](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/promo.png)

### Vérification d'existence de corrélation entre différents facteurs
![Correlations](http://cgphoto.cluster010.ovh.net/data/bolt_food/img/corr.png)
