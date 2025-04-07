**Disaster Detection and Crisis Management App** est une application web en temps réel qui permet de détecter et de suivre les catastrophes naturelles (incendies, séismes, etc.) dans la région de Lyon. L'application utilise une carte interactive pour indiquer la localisation des catastrophes, leur gravité, et la population affectée. Elle intègre également des prévisions basées sur l'intelligence artificielle pour évaluer les risques et prévoir l'impact des crises futures.

## Fonctionnalités

- **Carte interactive** : Affiche les catastrophes naturelles (incendies, séismes, tempêtes, etc.) sur une carte avec des codes couleur pour chaque type de catastrophe.
- **Filtrage avancé** : Permet de filtrer les catastrophes par type (incendie, séisme, tempêtes) et de visualiser des cartes thermiques (heatmap) pour chaque type d'événement.
- **Population affectée** : Affiche le nombre de personnes affectées par chaque crise en temps réel.
- **Événements actifs** : Liste des événements catastrophiques en cours et leur état de gestion (contenant, en cours, etc.).
- **Chronologie des événements** : Suivi des événements passés et futurs avec des détails précis (ex : zones industrielles de Lyon).
- **Prédiction de crise basée sur l'IA** : Utilise l'intelligence artificielle pour prédire la gravité des crises, leur durée, et les actions recommandées.
  - **Prédiction de l'impact de la crise** : Évalue l'étendue de la crise, le rayon d'impact et les ressources nécessaires.
  - **Planification des actions** : Recommande des actions spécifiques à prendre, comme la surveillance continue ou la préparation des équipes de déploiement.

## Technologies utilisées

- **Frontend** : React.js
- **Backend** : Node.js, Express.js
- **Carte interactive** : Google Maps API
- **Base de données** : MongoDB pour stocker les événements et informations en temps réel
- **IA / Machine Learning** : Python (si utilisé), TensorFlow / scikit-learn pour la prédiction des crises
- **API** : Intégration avec des API de données en temps réel pour détecter les catastrophes naturelles (par exemple, API de géolocalisation, API météo, etc.)

## Exemple d'un événement en temps réel

### Lyon Industrial Zone
- **Date et heure** : 07/04/2025 13:19:29
- **Gravité** : Moyenne
- **Statut** : Confiné
- **Population affectée** : 3 200 personnes
- **Ressources utilisées** : 12

### Lyon South Industrial Complex
- **Date et heure** : 07/04/2025 12:34:29
- **Gravité** : Moyenne
- **Statut** : Confiné
- **Population affectée** : 4 200 personnes
- **Ressources utilisées** : 11

## Prédiction de la crise - Lyon River District

- **Sévérité de la crise** : Modérée
- **Rayon d'impact** : 14.2 km
- **Durée estimée** : 41 heures
- **Ressources nécessaires** : Modérées (les ressources actuelles sont suffisantes)
- **Niveau de risque** : Diminution
- **Actions recommandées** :
  1. Continuer à surveiller les inondations dans le district de Lyon River
  2. Commencer à planifier les opérations de récupération
  3. Préparer les équipes d'évaluation des dégâts pour le déploiement

## Installation

### Prérequis

Avant de commencer, assurez-vous d'avoir installé :
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Python et dépendances IA](https://www.python.org/downloads/)
