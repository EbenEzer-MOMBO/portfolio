---
title: Nutriscan
publishDate: 2026-07-30 00:00:00
img: /assets/nutriscan.jpg
img_alt: Scan d'un repas avec Nutriscan
description: |
  PWA de suivi calorique avec analyse IA des repas et scan de codes-barres.
tags:
  - Santé
  - Intelligence artificielle
  - PWA
---

## Suivi Nutritionnel Assisté par l'IA

Nutriscan est une application web progressive conçue pour simplifier le suivi calorique. En photographiant un repas ou en scannant un code-barres, l'utilisateur obtient automatiquement les informations nutritionnelles, sans saisie manuelle fastidieuse.

### Points Clés

- Analyse des repas par vision IA (GPT-4o)
- Scan de codes-barres via OpenFoodFacts
- Dashboard calories et macronutriments personnalisés
- Journal alimentaire avec calendrier
- Authentification Google et Apple
- Expérience PWA installable sur mobile

### Une expérience mobile-first

<img width="1420" alt="Aperçu de Nutriscan" src="/assets/nutriscan1.jpg">

L'application guide l'utilisateur dès l'onboarding : profil morphologique, objectifs (perte de poids, maintien, prise de masse) et cibles caloriques. Le scan centralise l'ajout de repas, tandis que le journal et les tendances permettent de visualiser la progression au fil du temps.

### Stack technique

Frontend Next.js (App Router) et React, API Laravel (Sanctum), stockage cloud pour les photos de repas, et intégration OpenAI Vision pour la reconnaissance alimentaire.

><a href="https://nutriscan-ga.netlify.app/" target="_blank">Visiter la plateforme</a>