# Statistique-Exploratoire-Spatiale


Le cours de Statistique Exploratoire Spatiale est dispense par Mr Hema Aboubacar, [Analyste de Recherche a IFPRI](https://www.ifpri.org/profile/aboubacar-hema/) aux etudiants de l'[ENSAE - Dakar](https://www.ensae.sn/).


Bloc 1 – Fondations : Manipuler et visualiser les données (TP1–TP2)
Compétences acquises 🎯 : 

Importer, manipuler, visualiser et décrire les données spatiales de type vecteur (points, lignes, polygones) et raster (grilles de pixels).
Comprendre les métadonnées associées (système de coordonnées, résolution).
Calculer des statistiques descriptives de base (moyenne, min, max, surface, etc.).

Outils utilisés 💻 : 

Python : Bibliothèques geopandas, rasterio, matplotlib.
R : Packages sf, raster.
Google Earth Engine (GEE) : Pour le traitement de données spatiales.
Stata : Pour des analyses basiques.

Applications concrètes 🌍 : 

Prise en main des outils à travers des exercices basés sur des données administratives et des indicateurs de paludisme pour des pays comme le Sénégal, Madagascar, le Mali et la Côte d'Ivoire.

Bloc 2 – Premières analyses spatiales (TP3–TP4)
Compétences acquises 🎯 :

Réaliser des calculs zonaux : Croiser des données vectorielles (ex. régions d’un pays) avec des données raster (ex. carte du paludisme) pour calculer des statistiques par zone (ex. taux moyen de paludisme par région).
Effectuer une classification thématique : Regrouper les pixels d’un raster en classes (ex. "faible", "modéré", "grave") en fonction de seuils statistiques pour créer des cartes de risque.

Outils utilisés 💻 :

Google Earth Engine (GEE) : Traitement de grands ensembles de données via JavaScript ou Python.
R : Utilisation de ggplot2 pour des cartes statiques de haute qualité et leaflet pour des visualisations interactives.

Applications concrètes 🌍 :

Analyse de la prévalence du paludisme au Cameroun et au Sénégal pour identifier les zones à haut risque, utiles pour cibler les interventions sanitaires.

Bloc 3 – Analyses croisées et intégration de données (TP5–TP6 & TP11)
Compétences acquises 🎯 :

Intégrer des sources de données hétérogènes (sanitaires, démographiques comme WorldPop, événementielles comme les conflits).
Créer des rasters à partir de données ponctuelles (rasterisation) pour analyser la densité d’événements.
Construire des indicateurs composites, comme le Conflict Diffusion Indicator (CDI), en combinant plusieurs couches d’information.

Outils utilisés 💻 :

GEE : Manipulation de données globales via Python ou JavaScript.
Python : Manipulation fine des rasters et validation des calculs.
R : Analyse multi-niveaux et construction d’indicateurs composites.

Applications concrètes 🌍 :

Estimer le nombre d’enfants dans des zones à haut risque de paludisme au Niger.
Analyser la diffusion des conflits au Mali en croisant densité de population et lieux d’événements violents.

Bloc 4 – Ouverture vers la modélisation (TP7–TP9)
Compétences acquises 🎯 :

Initiation à la modélisation de la distribution d’espèces (SDM) pour prédire la présence d’une espèce en fonction de variables environnementales.
Comprendre des notions avancées comme l’autocorrélation spatiale.
Explorer de nouvelles sources de données.

Outils utilisés 💻 :

R : Utilisation du package sdmApp (application Shiny) pour faciliter l’accès à des modèles complexes comme MaxEnt et Random Forest.

Applications concrètes 🌍 :

Prédire la répartition géographique des espèces dans des contextes écologiques.
Explorer des thématiques comme le changement climatique et l’agriculture.

Bloc 5 – Applications avancées en télédétection (TP10–TP11)
Compétences acquises 🎯 :

Maîtriser la télédétection pour traiter des images satellitaires brutes.
Calculer des indices spectraux (ex. NDVI pour la végétation, NDWI pour l’eau, NDBI/UI pour les zones urbaines) pour extraire des informations thématiques.

Outils utilisés 💻 :

Python et R : Lecture des bandes d’images satellites (ex. Sentinel-2), application de formules mathématiques pixel par pixel, et exportation des cartes d’indices.

Applications concrètes 🌍 :

Suivi environnemental : Surveillance de la santé de la végétation, détection des zones inondées ou brûlées.
Applications en agriculture de précision, urbanisme, et sécurité (ex. analyse de l’humidité des sols, cartographie de l’étalement urbain).


Ce dépôt est conçu pour accompagner les apprenants dans leur progression à travers ces blocs, avec des exemples de code, des jeux de données et des tutoriels pour chaque TP.

## Data Credits

### TP 1

### TP 2

### TP 3

### TP 4

### TP 5

### TP 6

### TP 8


### TP 9


### TP 10

### TP 11



## License
This course material is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to re-use and adapt the material but are required to give appropriate credit to the original author as below:

## References


- Gandhi, Ujaval, 2023. Advanced Concepts in Google Earth Engine course. Spatial Thoughts. https://courses.spatialthoughts.com/gee-advanced.html
- Gandhi, Ujaval, 2021. End-to-End Google Earth Engine Course. Spatial Thoughts. https://courses.spatialthoughts.com/end-to-end-gee.html
- Gandhi, Ujaval, 2023. Creating Publication Quality Charts with GEE Course. Spatial Thoughts. https://courses.spatialthoughts.com/gee-charts.html

## Additional resources

- [Geospatial Software Design](https://resources.environment.yale.edu/courses/detail/754)
- [Google Earth Engine API documentation](https://developers.google.com/earth-engine/)
- [Google Earth Engine Developers forum](https://groups.google.com/g/google-earth-engine-developers)
- [Example scripts from Prof. Dana Tomlin’s handouts for his course on Geospatial Software Design](https://github.com/gee-community/example-scripts)
