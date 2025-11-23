
Point le plus haut – OSM + IGN Topographique
🔹 Description

Cet outil web permet de trouver le point d’altitude le plus élevé dans une zone donnée en France (ou ailleurs) via :

OpenStreetMap (OSM)

BD TOPO et RGE ALTI (IGN)

Modèle numérique de terrain SRTM (via OpenTopoData)

Fonctionne entièrement dans le navigateur, aucune installation serveur requise.

🔹 Fonctionnalités

Carte interactive Leaflet

Déplacement, zoom, couche OSM par défaut.

Couches IGN disponibles :

BD TOPO (IGN) : topographie vectorielle libre

RGE ALTI (IGN) : modèle numérique de terrain

Recherche de lieu

Entrer ville, adresse ou point d’intérêt.

Sélection via liste et affichage sur la carte.

Sélection de zone

Dessiner un rectangle sur la carte.

Une seule zone active à la fois.

Calcul du point le plus haut

Fusion des données OSM et SRTM (optionnel).

Filtrage automatique des valeurs aberrantes.

Résultat affiché sur la carte avec popup.

Export et impression

Export CSV avec nom, altitude et coordonnées.

Impression de l’aide intégrée.

Styles et fonds de carte

Styles prédéfinis : Pro, Nature, Dark.

Basemap : OSM, BD TOPO, RGE ALTI.

🔹 Instructions d’utilisation

Ouvrir l’outil via GitHub Pages ou en local (index.html).

Rechercher un lieu si besoin (facultatif).

Dessiner un rectangle sur la carte pour sélectionner la zone.

Configurer les options :

Échantillonnage SRTM (checkbox)

Résolution (grid size)

Fusion OSM/SRTM

Filtrage des aberrants

Cliquer sur “Trouver le point le plus haut”.

Exporter les données (CSV/GeoJSON) ou imprimer l’aide.

🔹 Conseils et limites

SRTM/OpenTopoData : limitation à ~80 points par requête, lat/lon à 1-2 décimales près.

Nominatim : 1 requête par seconde pour éviter le blocage.

IGN BD TOPO / RGE ALTI : couches libres via WMTS, pas de clé API nécessaire.

Couches non libres (SCAN, SCAN OACI) nécessitent une clé IGN et ne sont pas incluses.

🔹 Licence

Données OSM : ODbL
