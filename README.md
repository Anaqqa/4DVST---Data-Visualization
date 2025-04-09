# 4DVST---Data-Visualization
TP Jour 1-3 dans le cadre du cours 4DVST - Data Visualization

# Analyse de données de smartphones

## Description du projet

Ce projet analyse un jeu de données sur les smartphones pour identifier les tendances et relations entre différentes caractéristiques comme le prix, la note moyenne, les capacités techniques et les marques. L'objectif est de fournir des visualisations claires et informatives qui mettent en évidence les insights principaux de ce marché.

Le projet est structuré en plusieurs étapes :
1. Extraction des données à partir d'un fichier CSV
2. Prétraitement des données pour l'analyse
3. Calcul de statistiques descriptives
4. Génération de visualisations de base (Day 2)
5. Création de visualisations améliorées (Day 5)

## Stack technique

- **Langage** : Python 3.8+
- **Librairies principales** :
  - pandas : Manipulation et analyse des données
  - numpy : Calculs numériques
  - matplotlib : Visualisations de base
  - seaborn : Visualisations statistiques améliorées

## Source de la donnée

Le jeu de données utilisé contient des informations sur divers modèles de smartphones, leurs spécifications techniques et leurs prix.

Format des données :
```
brand_name,model,price,avg_rating,5G_or_not,processor_brand,num_cores,processor_speed,battery_capacity,fast_charging_available,fast_charging,ram_capacity,internal_memory,screen_size,refresh_rate,num_rear_cameras,os,primary_camera_rear,primary_camera_front,extended_memory_available,resolution_height,resolution_width
```

## Comment exécuter le code

1. Cloner le dépôt :
```
git clone https://github.com/votre-username/smartphone-analysis.git
cd smartphone-analysis
```

2. Installer les dépendances :
```
pip install pandas numpy matplotlib seaborn
```

3. Placer le fichier `smartphones.csv` dans le répertoire principal du projet

4. Exécuter le script principal :
```
python smartphone_analysis.py
```

5. Entrer votre nom et prénom lorsque demandé

6. Les visualisations seront générées dans deux dossiers :
   - `visualisations_basic/` : Visualisations de base (Day 2)
   - `visualisations_advanced/` : Visualisations améliorées (Day 5)

7. Un fichier Markdown `analyse_smartphone_visualisations.md` sera créé dans le répertoire principal
   - Convertir ce fichier en PDF pour le rendu final (voir les instructions ci-dessous)

## Conversion du Markdown en PDF

Pour convertir le fichier Markdown en PDF, plusieurs options s'offrent à vous :

1. **Services en ligne** :
   - Utilisez un service comme [Markdown to PDF](https://www.markdowntopdf.com/)
   - Importez le fichier `analyse_smartphone_visualisations.md`
   - Téléchargez le PDF généré

2. **Avec Pandoc** (si installé) :
   ```
   pandoc analyse_smartphone_visualisations.md -o analyse_smartphone_visualisations.pdf
   ```

3. **Avec VS Code** :
   - Installez l'extension "Markdown PDF"
   - Ouvrez le fichier `analyse_smartphone_visualisations.md`
   - Faites un clic droit et sélectionnez "Export (pdf)"
