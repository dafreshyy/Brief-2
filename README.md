# Brief-2
# Tableaux de Bord BI Retail — Analyse Ventes & Clients (Tableau)

## Contexte du Projet
Ce projet a été réalisé dans le cadre du **Brief 2** et simule un cas réel de **Business Intelligence** pour une entreprise de retail souhaitant remplacer ses rapports Excel statiques par une **solution BI dynamique et interactive**.

L’objectif est de concevoir **deux tableaux de bord Tableau interconnectés** — **Sales** et **Customer** — permettant d’analyser la performance **Year-over-Year (Année en cours vs Année précédente)** ainsi que le comportement et la fidélité des clients, à partir d’une **User Story métier** et de **maquettes fournies**.

## Objectifs du Projet
- Traduire des exigences métier réelles en visualisations pertinentes
- Appliquer une méthodologie BI structurée :  
  **Analyse ➝ Données ➝ Calculs ➝ Visualisations ➝ Dashboard**
- Maîtriser les calculs temporels dynamiques (**CY vs PY**)
- Utiliser des fonctions avancées Tableau (calculs de fenêtre, paramètres)
- Produire un design épuré, lisible et conforme aux standards UX/UI
- Mettre en place une interactivité fluide entre les vues

## Données Utilisées
Le projet repose sur **4 fichiers CSV** :

- **Customers** : informations clients  
- **Orders** : commandes, ventes, quantités, remises et profit  
- **Products** : catalogue produits (catégorie, sous-catégorie)  
- **Location** : informations géographiques (région, état, ville)

Les tables sont connectées autour de la table **Orders** via des relations (1-N).

## Dashboard Sales
**Objectif : analyser la performance commerciale**

### Fonctionnalités principales :
- KPI de synthèse :  
  - Ventes totales  
  - Profit  
  - Quantité  
  *(Année en cours vs Année précédente + variation YoY)*
- Tendances mensuelles CY / PY avec identification des mois **max / min**
- Analyse par sous-catégorie (Ventes & Profit)
- Tendances hebdomadaires avec moyenne et mise en évidence des écarts
- Filtres dynamiques (produits, localisation)
- Sélecteur d’année via paramètre

## Dashboard Customer
**Objectif : analyser la croissance et la fidélité client**

### Fonctionnalités principales :
- KPI de synthèse :
  - Nombre total de clients
  - Ventes moyennes par client
  - Nombre total de commandes  
  *(CY vs PY + variation YoY)*
- Tendances mensuelles clients (CY / PY)
- Distribution des clients selon le nombre de commandes (analyse de fidélité)
- Top 10 clients par profit avec :
  - Rang
  - Nom
  - Ventes
  - Profit
- Navigation fluide entre les dashboards
- Filtres et paramètres partagés

## Design & Interactivité
- Design épuré et cohérent
- Suppression des éléments graphiques inutiles (grilles, bordures)
- Couleurs sémantiques (performance positive / négative)
- Infobulles enrichies
- Navigation entre dashboards via boutons
- Paramètre global pour le choix de l’année analysée

## Outils Utilisés
- **Tableau Online**
- **GitHub** — gestion du code et des livrables
- **JIRA** — suivi du projet (Epic & Features)

## Critères de Qualité
- Exactitude des calculs CY / PY
- Cohérence des visualisations avec les objectifs métier
- Respect des bonnes pratiques BI et UX/UI
- Interactivité fonctionnelle et intuitive
- Modèle de données propre et calculs testés

## Période de Réalisation
Du **02/02/2026** au **06/02/2026**
