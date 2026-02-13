================================================================================
  NEXASTORE ANALYTICS — E-commerce Audit & Dashboard
================================================================================

  Author  : Redouane Hamecha — Data Analyst & IT Infrastructure
  Stack   : Python 3.9+ | Pandas | Jupyter | Chart.js
  Context : Academic portfolio project

![Aperçu du Dashboard](screenshot.png)
  [ English version below / Version française plus bas ]

--------------------------------------------------------------------------------
  DESCRIPTION
--------------------------------------------------------------------------------

This project transforms raw transactional sales data (~51,000 rows) into
actionable business insights and auto-generates a fully standalone HTML
dashboard — viewable in any browser, no server required.

The dataset simulates a realistic e-commerce audit across African markets,
and includes intentional data quality issues (broken encoding, mixed types,
missing values, duplicate columns) to practice real-world data wrangling.

--------------------------------------------------------------------------------
  FILES
--------------------------------------------------------------------------------

  NotebookAnalyctic.ipynb       The core. Data cleaning, EDA, and automated
                                HTML dashboard generation.

  DashboardNexaStore.html       The output. Interactive dashboard generated
                                by the notebook (Chart.js, standalone).

  Nexa_Store_Dataset_0_2.csv    The source. Raw transactional data with
                                intentional errors for cleaning practice.

--------------------------------------------------------------------------------
  METHODOLOGY
--------------------------------------------------------------------------------

  1. Data Cleaning
     - Corrupted encoding fix (e.g. \x92)
     - Type conversion (datetime, float)
     - Missing values & duplicate columns removal
     - Decimal separator normalization (comma -> dot)

  2. Exploratory Data Analysis (EDA)
     - Revenue, net profit, margins by category / sub-category
     - Breakdown by region, market segment, shipping mode
     - Logistics impact: shipping delay vs. profitability
     - Sales / Profit scatter plot per product (log scale)

  3. Dashboard Generation
     - Aggregated data injected as JSON into an HTML/JS template
     - Output is 100% self-contained (no Python needed to view it)

--------------------------------------------------------------------------------
  USAGE
--------------------------------------------------------------------------------

  # Install dependencies
  pip install pandas matplotlib seaborn numpy jupyter

  # Run the notebook
  jupyter notebook NotebookAnalyctic.ipynb

  To view the dashboard without running any code:
  -> Simply open DashboardNexaStore.html in your browser.

--------------------------------------------------------------------------------
  LINKS
--------------------------------------------------------------------------------

  LinkedIn  : https://www.linkedin.com/in/redouanehamecha
  Portfolio : https://redouanehamecha.github.io/

================================================================================
================================================================================
  NEXASTORE ANALYTICS — Audit E-commerce & Dashboard          [ VERSION FR ]
================================================================================

  Auteur  : Redouane Hamecha — Data Analyst & Infrastructure IT
  Stack   : Python 3.9+ | Pandas | Jupyter | Chart.js
  Contexte : Projet portfolio académique

--------------------------------------------------------------------------------
  DESCRIPTION
--------------------------------------------------------------------------------

Ce projet transforme des données de ventes brutes (~51 000 lignes) en insights
stratégiques exploitables et génère automatiquement un dashboard HTML standalone
— consultable dans n'importe quel navigateur, sans serveur Python.

Le dataset simule un audit e-commerce réaliste sur les marchés africains et
contient des erreurs volontaires (encodage cassé, types mixtes, valeurs
manquantes, colonnes dupliquées) pour pratiquer le nettoyage de données réel.

--------------------------------------------------------------------------------
  FICHIERS
--------------------------------------------------------------------------------

  NotebookAnalyctic.ipynb       Le cerveau. Nettoyage, EDA et génération
                                automatique du dashboard HTML.

  DashboardNexaStore.html       Le résultat. Dashboard interactif généré
                                par le notebook (Chart.js, standalone).

  Nexa_Store_Dataset_0_2.csv    La source. Données brutes transactionnelles
                                avec erreurs volontaires pour l'exercice.

--------------------------------------------------------------------------------
  MÉTHODOLOGIE
--------------------------------------------------------------------------------

  1. Data Cleaning
     - Correction des encodages corrompus (ex. \x92)
     - Conversion de types (datetime, float)
     - Suppression des valeurs manquantes et colonnes dupliquées
     - Normalisation des séparateurs décimaux (virgule -> point)

  2. Analyse Exploratoire (EDA)
     - CA, profit net, marges par catégorie / sous-catégorie
     - Analyse par région, segment de marché, mode d'expédition
     - Impact logistique : délais d'expédition vs rentabilité
     - Scatter plot Ventes / Profit par produit (échelle log)

  3. Génération du Dashboard
     - Données agrégées injectées en JSON dans un template HTML/JS
     - Fichier HTML 100 % autonome (aucune installation pour le consulter)

--------------------------------------------------------------------------------
  UTILISATION
--------------------------------------------------------------------------------

  # Installer les dépendances
  pip install pandas matplotlib seaborn numpy jupyter

  # Lancer le notebook
  jupyter notebook NotebookAnalyctic.ipynb

  Pour consulter le dashboard sans exécuter de code :
  -> Ouvrir directement DashboardNexaStore.html dans votre navigateur.

--------------------------------------------------------------------------------
  LIENS
--------------------------------------------------------------------------------

  LinkedIn  : https://www.linkedin.com/in/redouanehamecha
  Portfolio : https://redouanehamecha.github.io/

================================================================================
