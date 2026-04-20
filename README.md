# Réservation Hôtel

## Description
Ce projet est une application web de réservation d'hôtel développée avec React pour le frontend et Node.js pour le backend. Il permet aux utilisateurs de consulter les chambres disponibles, effectuer des réservations et gérer les réservations existantes.

## Fonctionnalités
- Consultation des chambres disponibles
- Réservation de chambres
- Gestion des réservations (modification, annulation)
- Interface d'administration
- Authentification des utilisateurs
- Envoi d'emails de confirmation

## Structure du projet
- `client/` : Application frontend React avec Vite
- `server/` : API backend Node.js avec Express
- `docs/` : Documentation de déploiement
- `scripts/` : Scripts de déploiement

## Installation

### Prérequis
- Node.js (version 16 ou supérieure)
- npm ou yarn
- Base de données (configurée dans `server/src/config/db.js`)

### Installation du frontend
```bash
cd client
npm install
npm run dev
```

### Installation du backend
```bash
cd server
npm install
npm start
```

## Utilisation
1. Démarrer le serveur backend
2. Démarrer le client frontend
3. Accéder à l'application via le navigateur

## Déploiement
Consultez les guides dans le dossier `docs/` pour le déploiement sur AWS.

## Auteur
Alioune KAMARA

## Licence
Ce projet est sous licence MIT.