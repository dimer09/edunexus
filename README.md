# EduNexus

**Plateforme intelligente de gestion académique adaptée aux universités en RDC.**

EduNexus centralise la gestion académique au sein d'une application web et mobile, avec prise en charge du mode hors ligne et un assistant intelligent facilitant l'accès aux informations académiques.

[![Démo en ligne](https://img.shields.io/badge/Demo-en%20ligne-brightgreen)](https://edunexus-q95r.onrender.com/)

![Aperçu d'EduNexus](assets/Screenshot_20260604-193722.png)

## Problématique

La gestion académique dans de nombreux établissements repose encore sur des outils dispersés et des processus manuels. Les contraintes de connectivité compliquent également l'accès aux informations.

EduNexus propose une solution centralisée conçue pour répondre à ces besoins.

## Fonctionnalités

- **Gestion académique :** étudiants, promotions, horaires, notes et bulletins.
- **Présences sécurisées :** QR codes et codes OTP pour renforcer le contrôle des présences.
- **Mode hors ligne :** consultation des données locales et synchronisation au retour de la connexion.
- **Assistant intelligent :** utilisation d'un LLM et du RAG pour interroger les informations académiques et faciliter l'identification des étudiants à risque.
- **Multi-plateforme :** interfaces web et mobile.

## Stack technique

| Couche | Technologies |
|---|---|
| Web | React, TypeScript, Vite |
| Mobile | React Native, Expo |
| Backend | Node.js, Express |
| Base de données | PostgreSQL, Supabase |
| Stockage local | IndexedDB, SQLite |
| Gestion des données | TanStack Query, Zustand |
| Assistant IA | LLM, RAG, pgvector |
| Déploiement | Render, Supabase |

## Défis techniques

- **Connectivité limitée :** stockage local des données nécessaires et synchronisation lorsque le réseau est disponible.
- **Fiabilité des présences :** combinaison de mécanismes de vérification pour limiter les tentatives de fraude.
- **Fiabilité des réponses IA :** le RAG permet à l'assistant de s'appuyer sur des informations pertinentes plutôt que de dépendre uniquement des connaissances générales du modèle.

## Démonstration

Application web : [edunexus-q95r.onrender.com](https://edunexus-q95r.onrender.com/)

