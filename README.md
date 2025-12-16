# Projet Math-Appli 1A – Modélisation des accidents routiers en France

Ce projet vise à **modéliser la sévérité et la fréquence des accidents routiers en France**
à partir des données ONISR 2021.  
Trois approches statistiques sont mises en œuvre :

1. Modèle linéaire  
2. Méthode de partitionnement (clustering)  
3. Modèle de fréquence  

---

## Table des matières

- [Arborescence du projet](#arborescence-du-projet)  
- [Étape 1 : Exportation des données](#étape-1--exportation-des-données)  
- [Étape 2 : Modèle linéaire](#étape-2--modèle-linéaire)  
- [Étape 3 : Méthode de partitionnement (clustering)](#étape-3--méthode-de-partitionnement-clustering)  
- [Étape 4 : Modèle de fréquence](#étape-4--modèle-de-fréquence)  

---

## Arborescence du projet

- `description/`  
  - `sujet*.md` : sujet du projet au format Markdown  
  - `sujet.pdf` : sujet du projet au format PDF  

- `data/`  
  - `ONISR-2021.csv.zip` : données brutes ONISR 2021  
  - `description-des-bases-de-donnees-annuelles.pdf` : description des variables  

- `Regression_linéaire/`  
  - `reg_lineaire2.Rmd` : implémentation du modèle linéaire  
  - `reg_lineaire2.pdf` : résultats du modèle linéaire  

- `clustering/`  
  - `nettoyage_donnees_clustering.Rmd` : préparation des données  
  - `clustering.Rmd` : implémentation de la méthode de partitionnement  
  - `clustering.pdf` : résultats du clustering  

- `frequence/`  
  - `frequence.Rmd` : implémentation du modèle de fréquence  
  - `frequence.pdf` : résultats du modèle de fréquence  

- `rapport/`  
  - `rapport.tex` : rapport collectif  

- `README.md` : ce fichier  

---

## Étape 1 : Exportation des données

1. Décompresser le fichier `ONISR-2021.csv.zip` situé dans le dossier `data/`.  
2. Vérifier que le fichier CSV extrait se trouve bien dans le dossier `data/`.  

---

## Étape 2 : Modèle linéaire
Fichier qui présente la construction du score de sévérité et l'élaboration de 3 modèles de régression linéaire. Ces modèles cherchent à expliquer ce score en fonction de variables telles que les caractéristiques de l'accident, le lieu, les véhicules et les usagers impliqués. 

**Instructions :**

1. 
---

## Étape 3 : Méthode de partitionnement (clustering)

Le clustering permet de **regrouper les accidents selon des caractéristiques similaires**
afin d’identifier des profils types d’accidents.

**Instructions :**

1. Lancer RStudio et se placer dans le dossier `clustering/`.  
2. Exécuter le script `nettoyage_donnees_clustering.Rmd` pour préparer les données.  
3. Vérifier que le fichier `donnees_clustering.csv` est bien généré dans le dossier `data/`.  
4. Ouvrir `clustering.Rmd` et exécuter toutes les cellules pour appliquer la méthode de partitionnement.

---

## Étape 4 : Modèle de fréquence

Petite déscription et instruction comment lancer les fichiers qui implémente le modèle.

1. **Instructions :**

