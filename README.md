# Project Machine learning : Predict the mark on student files for an entrance examination to a group of engineering schools

Report and code written in French by PHAM Dong Pha and MENARD June Camille

Problématique 

Dans ce travail, nous allons prédire la note de dossier obtenue par un candidat. Celle-ci est calculée dans le cadre d’un concours d'entrée à un groupe d'écoles d'ingénieurs. Le but est de prédire la note sur dossier en fonction de l'ensemble des données fournies. Au-delà de cela, il s'agit de comprendre quels sont les paramètres déterminants dans l'évaluation du dossier, voire d'approcher ou retrouver l'algorithme. Les données ont été complètement anonymisées et les différentes notes décalées de quantités aléatoires. Le but est donc, à partir de l'ensemble des données disponibles, de prédire la note de dossier obtenue par un candidat.

Nous choisissons les tâches principales du projet:

- Lire le jeu de données disponible
- Prétraiter le jeu de données (Imputation, suppression des colonnes indésirables sans affecter la précision, traitement des valeurs aberrantes, …etc.)
- Visualiser le jeu de données
- Effectuer une analyse exploratoire des données (statistiques descriptives, corrélation, sélection de caractéristiques, réduction de dimensionnalité, …etc)
- Utiliser des algorithmes d'apprentissage automatique différents pour prédire la note
- Après avoir identifié le meilleur algorithme, utiliser toutes les données d'entraînement (train.csv) pour créer le modèle et prédire la note finale de l'examen pour les données de test fournies (test.csv)

