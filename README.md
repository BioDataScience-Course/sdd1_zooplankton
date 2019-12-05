# Analyse d'image du zooplancton provenant de Tuléar (Madagascar)

## Avant-propos

Ce dernier est un projet qui va évoluer avec votre progression dans les différents modules. Pour ce faire, suivez avec attention les attendus pour chaque module.

Il est possible que ce document évolue au cours du temps. N'hésitez pas à aller vérifier le lien suivant afin de voir les modifications dans les consignes : https://github.com/BioDataScience-Course/sdd1_zooplankton

Module 1

Objectif

Créer votre site web scientifique personnel
Etat de progression

A la fin de ces modules, vous devez avoir créer votre site web. Ce site doit comprendre les informations de base afin de vous identifier (il ne s'agit donc pas de laisser le template de base sans aucune modification).

## Module 3 

### Objectif

- Organiser un projet en plusieurs sous-dossiers afin de décrire les données du jeu de données `zooplankton` 
- Créer un rapport d'analyse en R Markdown organisé en plusieurs sections afin de rapporter le fruit de vos recherches sur ces données. 

Ce document fruit de votre analyse doit suivre la structuration suivante :

- une section introduction qui presente le sujet de ce projet
- une section résultats ou descriptions qui comprend les graphiques réalisés et commentés

### Partie 1

- Explorez les données provenant du jeu de données et proposez **au moins** 10 graphiques variés sur les données. Ces graphiques doivent être commenté. 

Pour importer ces données vous devez employer les instructions suivantes

```
# Importation du jeu de données
zooplankton <- read( file = "zooplankton", package = "data.io", lang = "fr")
```

## Partie 2

Après avoir étudié le jeu de données dans son ensemble, étudiez plus en précision les copépodes 

- Proposez  **au moins** 10 graphiques afin de les comparer. 

- Rapportez le fruit de vos recherches dans un document structuré.

Pour filtrer les données, vous devez employer les instructions suivantes
 
```
# Réduction du jeu de données zooplankton
zooplankton_sub <- filter(zooplankton, class %in% c("Poecilostomatoid", "Calanoid", "Cyclopoid", "Harpacticoid"))
```

---- 

## Module 4

### Etat d'avancement

A la fin de ce module votre rapport doit contenir en plus des graphiques demandé précédement, au moins 2 graphiques inédits. Ils ne peuvent donc pas avoir été expliqué dans le cours. Tous les graphiques doivent être commentés.

----

## Module 5-6

### Etat d'avancement

A la fin de ces modules votre rapport doit contenir au moins 2 tableaux qui décrivent les données. N'hésitez pas à retravailler le tableau de données si nécessaire.

### Challenge

Une série d'exercices vous sont proposé à la fin du module 5 sous la forme d'un challenge. Consignez le résultat de vos exercices dans un fichier Rmd spécifique.

----



