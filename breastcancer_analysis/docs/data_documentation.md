# Documentation des données

## Source du dataset

- Archive UCI Machine Learning Repository :  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## Description générale

Le dataset Breast Cancer Wisconsin (Diagnostic) contient 569 observations issues d’analyses de masses mammaires par ponction à l’aiguille fine (FNA).

L’objectif est de prédire le diagnostic :
- M = Malin
- B = Bénin

## Créateurs

- Dr. William H. Wolberg — Département de chirurgie générale, Université du Wisconsin
- W. Nick Street — Département d’informatique, Université du Wisconsin
- Olvi L. Mangasarian — Département d’informatique, Université du Wisconsin

## Caractéristiques des données

- Nombre d’observations : 569
- Nombre d’attributs : 32
  - 1 identifiant
  - 1 variable cible (diagnostic)
  - 30 variables numériques

## Variables explicatives

Dix caractéristiques morphologiques sont calculées pour chaque noyau cellulaire :

- radius
- texture
- perimeter
- area
- smoothness
- compactness
- concavity
- concave points
- symmetry
- fractal dimension

Pour chacune, sont calculés :
- la moyenne
- l’erreur standard
- la valeur maximale ("worst")

Total : 30 variables numériques.

## Répartition des classes

- 357 bénins
- 212 malins

## Valeurs manquantes

Aucune valeur manquante.
