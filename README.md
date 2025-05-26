# 🥗 OC - Projet 3 : Préparez des données pour un organisme de santé publique

Ce projet est réalisé dans le cadre du parcours *AI Engineer* d’OpenClassrooms, en partenariat avec **Santé publique France**.  
L’objectif est de contribuer à l’amélioration de la base de données **Open Food Facts**, en préparant un système de **suggestion ou d’auto-complétion** permettant d’aider les utilisateurs à mieux renseigner les produits alimentaires.

---

## 🎯 Objectif

> Nettoyer, explorer et analyser le jeu de données Open Food Facts afin d’évaluer la faisabilité d’un système de suggestion automatisée pour les champs incomplets.

---

## 📊 Travaux réalisés

Le projet est divisé en deux notebooks : un dédié au **nettoyage**, l’autre à l’**analyse exploratoire et statistique**.

### 1. Nettoyage et préparation (`P3_Nettoyage.ipynb`)
- Sélection des variables à fort taux de valeurs manquantes
- Méthodes de traitement :
  - suppression de colonnes ou d’observations
  - imputation conditionnelle ou statistique
  - identification et correction des valeurs aberrantes
- Automatisation du pipeline de nettoyage (adaptatif à des modifications futures de la base)

### 2. Analyse exploratoire (`P3_Analyses.ipynb`)
- Analyse univariée (histogrammes, boxplots, diagrammes circulaires…)
- Analyse multivariée :
  - Corrélations entre variables
  - Création ou sélection de nouvelles variables
  - Tests statistiques de significativité
- Visualisations variées et pédagogiques pour communication non-technique

---

## 🔐 RGPD

Bien que les données n’incluent pas d’informations personnelles, une **présentation dédiée au RGPD** a été produite. Elle explique comment le projet respecte les 5 grands principes :

1. Finalité claire
2. Minimisation des données
3. Exactitude
4. Limitation de conservation
5. Sécurité et transparence

---

## 📁 Arborescence du projet

```
├── P3_Nettoyage.ipynb              → Pipeline de nettoyage automatisé
├── P3_Analyses.ipynb               → Analyses statistiques et visualisations
├── données/                        → Dataset Open Food Facts
├── presentation_rgpd.pptx          → Présentation RGPD
├── rapport_exploration.pdf         → Rapport de faisabilité
└── README.md                       → Présentation du projet
```

---

## 🛠️ Technologies utilisées

- Python
- Jupyter Notebook
- `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`

---

## 🧠 Auteur

Projet réalisé par **AnthonyJVID** dans le cadre du parcours *AI Engineer* chez OpenClassrooms.

---

## 📄 Licence

Projet à but pédagogique basé sur des données publiques issues de [Open Food Facts](https://world.openfoodfacts.org/data).
