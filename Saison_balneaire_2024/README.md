# Projet : Rapportage de la saison balnéaire 2024

## Contexte

Ce projet s'inscrit dans le cadre de la SAÉ « Bases de données et langage SQL ».  
L'objectif est de suivre la qualité des eaux de baignade en France durant la saison 2024, conformément à la directive européenne 2006/7/CE.  

Les données proviennent de fichiers CSV officiels et contiennent :
- Les sites de baignade
- Les événements survenus (interdictions sanitaires, cyanobactéries, etc.)
- Les analyses bactériologiques (Escherichia coli, entérocoques intestinaux)
- Les départements et régions de France

## Objectif du projet

- Créer et modéliser une base de données SQL avec un **AGL** (outil de modélisation)  
- Générer automatiquement le script de création des tables à partir du modèle physique  
- Peupler la base à partir des fichiers CSV officiels  
- Comparer la modélisation manuelle et celle produite par l’AGL  

## Contenu du dépôt

- `AGL.png` : modèle physique réalisés avec l’AGL  
- `scripts` : scripts SQL générés automatiquement par l’AGL et scripts manuels  
- `fichiers_csv/` : fichiers CSV utilisés pour peupler la base de données  

## Utilisation

1. Cloner le dépôt :
```bash
git clone https://github.com/abassekaderbhai-dev/SQL.git
2. Aller dans le dossier du projet 'balnéaire' et exécuter les scripts SQL dans votre SGBD.
3. Consulter les modèles AGL pour comprendre la structure de la base de données.
