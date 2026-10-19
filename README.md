# Projet de fin de formation en data analyse
![logo](https://images.cyril-gervais.com/image/4b6ace53-a843-4080-bc5e-52c2cdb4e0c7.webp)

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

| Nom du fichier |
|-----------------------------------------------------------------------------------------------------------|
| ![CSV Lines Badge](https://img.shields.io/badge/customers%2Ecsv-378%20observations-informational)         |
| ![CSV Lines Badge](https://img.shields.io/badge/products%2Ecsv-1.711.616%20observations-informational)    |
| ![CSV Lines Badge](https://img.shields.io/badge/transactions%2Ecsv-807.676%20observations-informational)  |

Données collectées par [Foxintelligence](https://nielseniq.com/global/en/products/foxintelligence-by-nielseniq/)

## Temporalité du jeu de données
![Timeline](https://images.cyril-gervais.com/image/b056869a-d264-4264-9603-298e81ebcd1d.webp)

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
![Concurrents](https://images.cyril-gervais.com/image/632a9bde-0d45-4579-8331-04cb3ec1c10d.webp)

### Chiffre d'affaires par concurrent et par région française
![CA](https://images.cyril-gervais.com/image/b0317c10-7b28-4e72-afd1-b755a6fe3531.webp)

### Répartition des commandes dans la journée
![Heures](https://images.cyril-gervais.com/image/39845cdf-d81a-472f-88bb-3654fd686a65.webp)

### Evolution des frais dans le temps
![Frais](https://images.cyril-gervais.com/image/584dfc5c-2cb3-4513-8e89-b7ec0b048e6c.webp)

### Commandes en promotion par mois et par concurrent
![Promo](https://images.cyril-gervais.com/image/c82b5b4f-876d-487d-8b3f-dfcd49ce2f9b.webp)

### Vérification d'existence de corrélation entre différents facteurs
![Correlations](https://images.cyril-gervais.com/image/3bc5e245-944d-4960-b483-067509ee9afa.webp)
