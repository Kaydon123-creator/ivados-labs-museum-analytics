# Ingénierie de données + Régression linéaire (Musées & Population)

Ce projet consiste à construire un petit pipeline en Python pour :

- récupérer la liste des musées les plus visités depuis Wikipédia,
- enrichir ces données avec la population des villes (dataset Kaggle),
- analyser la relation entre la population d’une ville et la fréquentation de ses musées à l’aide d’une régression linéaire,
- visualiser la tendance obtenue.

## Étapes du projet

1. Scraping du tableau Wikipédia (musées les plus visités)
2. Chargement du dataset des villes (population)
3. Nettoyage et normalisation des données
4. Simulation jointure musées ↔ villes (population) 
5. Jointure musées ↔ villes
6. Analyse exploratoire
7. Régression linéaire
8. Visualisation des résultats

## Technologies utilisées
- **pandas** : manipulation, nettoyage et jointure des données  
- **seaborn** : visualisation statistique (graphiques exploratoires)  
- **matplotlib** : visualisations (nuages de points, droite de régression)  
- **scikit-learn** : entraînement et évaluation du modèle de régression linéaire  
- **sweetviz** : analyse exploratoire automatique des DataFrames  
- **re (regex)** : nettoyage et parsing de chaînes de caractères 