# 🗺️ Visualisation Géographique des Villes avec Folium

Ce projet Python permet d'afficher sur une carte interactive des villes de France ainsi que leur poupulation et des capitales d'Europe à l'aide de fichiers CSV, grâce à leurs coordonnées géographiques et leur population. 

La carte est générée avec la bibliothèque Folium et sauvegardée au format HTML.

## 🔧 Prérequis

Assurez-vous d’avoir installé les bibliothèques nécessaires :

- **Pandas**
- **Folium**

## 📁 Structure du projet

├── carte.ipynb             
├── Dataset/ \
│   └── Villes.csv \
|   └── Capitales.csv           
├── Carte_Europe.html        
└── README.md                

## 📄 Format attendu des fichiers .csv
Le fichier CSV doit contenir les colonnes suivantes :

ville	latitude	longitude	population \
Paris	48.8566	2.3522	2148327 \
Lyon	45.7640	4.8357	513275 \
Marseille	43.2965	5.3698	861635

## 🚀 Lancer le projet
Pour lancer le script, il faut exécuter le code grâce au bouton directement dans le notebook Python


## 🔍 Résultat
Ouvrez le fichier Carte_Europe.html dans votre navigateur pour explorer la carte interactive.

## 🧠 Technologies utilisées
- **Python**
- **Pandas :** pour le chargement et la manipulation des données
- **Folium :** pour créer des cartes interactives basées sur Leaflet.js

## Autrices
[Marya Bouchene](https://github.com/marya213)

[Tyfenn Le Dévéhat](https://github.com/tyfld)
