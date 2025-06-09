🗺️ Visualisation des Villes avec Folium
Ce projet Python permet d'afficher sur une carte interactive les villes d’un fichier CSV, avec leurs coordonnées géographiques et leur population. La carte est générée avec la bibliothèque Folium et sauvegardée au format HTML.

🔧 Prérequis
Assurez-vous d’avoir installé les bibliothèques nécessaires :

bash
Copier
Modifier
pip install pandas folium
📁 Structure du projet
graphql
Copier
Modifier
.
├── main.py                  # Script principal de visualisation
├── Dataset/
│   └── Villes.csv           # Fichier CSV contenant les données des villes
├── Carte_Villes.html        # Carte interactive générée (en sortie)
└── README.md                # Ce fichier
📄 Format attendu du fichier Villes.csv
Le fichier CSV doit contenir les colonnes suivantes :

ville	latitude	longitude	population
Paris	48.8566	2.3522	2148327
Lyon	45.7640	4.8357	513275
Marseille	43.2965	5.3698	861635

🚀 Lancer le projet
Exécute le script Python :

bash
Copier
Modifier
python main.py
Cela va :

Charger les données depuis ./Dataset/Villes.csv

Générer une carte centrée sur la France

Ajouter un marqueur pour chaque ville avec son nom et sa population

Sauvegarder le tout dans Carte_Villes.html

🔍 Résultat
Ouvrez le fichier Carte_Villes.html dans votre navigateur pour explorer la carte interactive.

🧠 Technologies utilisées
Python

Pandas : pour le chargement et la manipulation des données

Folium : pour créer des cartes interactives basées sur Leaflet.js
