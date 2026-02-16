# Breast Cancer Wisconsin Analysis

## Description

Ce projet analyse le dataset **Breast Cancer Wisconsin (Diagnostic)** provenant de l'UCI Machine Learning Repository.

Les données sont issues d’images numérisées de ponctions à l’aiguille fine (FNA) de masses mammaires.  
Les variables décrivent les caractéristiques morphologiques des noyaux cellulaires et permettent de prédire si une tumeur est bénigne (B) ou maligne (M).

Le dataset contient 569 observations et 30 variables explicatives.

## Objectifs

- Explorer et visualiser les caractéristiques morphologiques des cellules
- Comprendre les différences entre tumeurs bénignes et malignes
- Identifier les variables les plus discriminantes
- Appliquer des méthodes de classification
- Évaluer la performance des modèles prédictifs

## Installation et Configuration

### Prérequis
- Python 3.10.0
- Gestionnaire de paquets : `condavenv`

### Installation des dépendances
```bash
pip install -r requirements.txt
```

## Méthodologie

1. **Collecte des données** : Recherche et extraction de datasets pertinents sur l'état des océans
2. **Nettoyage des données** : Vérification des valeurs manquantes et cohérence des variables
3. **Analyse exploratoire (EDA)** : Visualisations, statistiques descriptives 
4. **Modélisation** : Classification (régression logistique)
5. **Évaluation** : Accuracy, matrice de confusion, validation croisée

### Documents de référence
- **[Documentation des données](breastcancer_analysis/docs/data_documentation.md)** : Sources et descriptions détaillées des datasets utilisés

*Projet réalisé dans le cadre d'un cours de Data Visualisation*