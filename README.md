
# 🗺️ Visualisation des Villes Françaises et des Capitales Européennes avec Folium

Ce projet Python affiche sur une carte interactive les villes françaises ainsi que les capitales des pays européens à partir de deux fichiers CSV. La carte est générée avec la bibliothèque **Folium** et sauvegardée au format HTML.

---

## 🔧 Prérequis

Assurez-vous d’avoir installé les bibliothèques nécessaires :

```bash
pip install pandas folium

📁 Structure du projet
bash
Copier
Modifier
.
├── main.py                          # Script principal de visualisation
├── Dataset/
│   ├── Villes.csv                   # Données des villes françaises
│   └── Capitales.csv                # Données des capitales européennes
├── Carte_Villes_Et_Capitales.html  # Carte interactive générée (en sortie)
└── README.md                       # Ce fichier

📄 Format attendu des fichiers CSV
Villes.csv
ville	latitude	longitude	population
Paris	48.8566	2.3522	2148327
Lyon	45.7640	4.8357	513275
Marseille	43.2965	5.3698	861635

Capitales.csv
capitale	pays	latitude	longitude
Paris	France	48.8566	2.3522
Berlin	Allemagne	52.5200	13.4050
Rome	Italie	41.9028	12.4964

🚀 Lancer le projet
Exécutez le script Python :

bash
Copier
Modifier
python main.py
Ce script va :

Charger les données des villes françaises depuis ./Dataset/Villes.csv

Charger les données des capitales depuis ./Dataset/Capitales.csv

Créer une carte centrée sur l'Europe

Ajouter des marqueurs rouges pour chaque ville française avec son nom et sa population

Ajouter des marqueurs bleus pour chaque capitale avec son nom et son pays

Sauvegarder la carte dans Carte_Villes_Et_Capitales.html

🔍 Résultat
Ouvrez le fichier Carte_Villes_Et_Capitales.html dans votre navigateur pour explorer la carte interactive.

🧠 Technologies utilisées
Python

Pandas : pour le chargement et la manipulation des données

Folium : pour créer des cartes interactives basées sur Leaflet.js
