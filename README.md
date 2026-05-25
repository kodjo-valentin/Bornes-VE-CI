# ⚡ Cartographie Interactive du Réseau de Recharge pour Véhicules Électriques en Côte d'Ivoire

> **Projet de fin d'études — Licence Professionnelle en Géomatique et Stratégies Spatiales (UFHB)** > *Outil d'aide à la décision pour la planification des infrastructures de mobilité durable.*

Un projet conçu pour cartographier, analyser et optimiser l'implantation des stations de recharge pour véhicules électriques en Côte d'Ivoire (focus initial sur Abidjan). Cette application web interactive permet aux décideurs publics et aux opérateurs privés d'identifier les opportunités stratégiques et les zones blanches du réseau.

🚀 **[CLIQUEZ ICI POUR TESTER L'APPLICATION EN LIVE](https://ton-pseudo.github.io/ton-depot/)**

---

## 🎯 Problématique & Enjeux Stratégiques
La transition vers la mobilité électrique en Côte d'Ivoire est en marche, mais l'adoption des véhicules dépend fortement de la disponibilité et de la visibilité des infrastructures de recharge. 
Cet outil répond à trois défis majeurs :
1. **Visibilité :** Centraliser l'information pour les utilisateurs (localisation, puissance, type de charge).
2. **Analyse Concurrentielle :** Permettre aux opérateurs (Pétro Ivoire, TotalEnergies, CIE, etc.) de visualiser le positionnement de leurs concurrents.
3. **Planification Spatiale :** Identifier les zones sous-équipées grâce à des analyses d'accessibilité.

## ✨ Fonctionnalités Clés
* **Cartographie Dynamique :** Visualisation des stations actives et à venir avec des marqueurs personnalisés par opérateur.
* **Filtres Avancés :** * Par type de charge (Rapide, Lente, Solaire).
  * Par statut (Actif, À venir).
  * Par opérateur du marché.
* **Analyse d'Accessibilité (Zones de couverture) :** Génération automatique de zones tampons (*buffers* de 5 km) autour des stations pour mesurer le taux de couverture réel du territoire.
* **Interface Responsive & Dark Mode :** Conçue pour une lecture optimale des données géospatiales de jour comme de nuit.

## 🛠️ Stack Technique
* **Frontend :** HTML5, CSS3 (Design personnalisé, Thème sombre), JavaScript (ES6).
* **Cartographie Web :** Leaflet.js / CartoDB Basemaps.
* **Données & SIG :** Traitement des données spatiales, calcul des coordonnées géographiques et des zones d'influence.

## 📈 Perspectives de Développement
* Connexion à une base de données spatiale (**PostGIS**) pour des requêtes en temps réel.
* Intégration d'un module de calcul d'itinéraire optimal vers la station la plus proche.
* Dashboard statistique complet (taux de couverture par commune, ratio bornes rapides/lentes).

---

## 👤 Auteur
**KODJO Kablan Valentin Martial**  * Étudiant en Licence Professionnelle Géomatique et Stratégies Spatiales – Université Félix Houphouët-Boigny (UFHB)
* 💼 profil LinkedIn: https://www.linkedin.com/in/kablan-valentin-martial-kodjo-154993311/?locale=fr
* ✉️ Email: k90089994@gmail.com
