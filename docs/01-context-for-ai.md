# Context Rapide pour IA - Projet Sparring

## Le Projet en 30 secondes
**Quoi** : App mobile pour matcher des boxeurs thaïlandais qui veulent s'entraîner ensemble  
**Comment** : Interface type "Tinder" + géolocalisation + chat + planning  
**Qui** : 2 personnes (humain = DevOps/tests, IA = développement)  
**Quand** : 12-18 mois pour MVP viable  

## Stack Technique Choisie
Frontend: React Native Expo
Backend: Node.js + Express
Database: MongoDB Atlas
Images: Cloudinary
Deploy: Heroku
Maps: Google Maps API
Push: Expo Notifications

## Features MVP (par ordre de priorité)
1. **Auth** : Register/Login email
2. **Profils** : Nom, niveau, photo, bio, localisation  
3. **Matching** : Voir boxeurs à proximité, like/pass
4. **Chat** : Messagerie entre matchs
5. **Planning** : Proposer créneaux de sparring
6. **Historique** : Sessions passées

## Rôles dans l'équipe
**Humain (vous)** :
- Configuration serveurs et déploiements
- Tests sur mobile iOS/Android
- Feedback UX et validation features  
- Gestion des comptes services (Heroku, MongoDB, etc.)

**IA (Claude)** :
- Architecture et développement code
- APIs backend et logiques métier
- Interface mobile React Native
- Documentation technique détaillée

## Contraintes Importantes
- **Simplicité first** : Solutions robustes plutôt qu'élégantes
- **Documentation** : Code ultra-commenté, instructions step-by-step
- **Tests réels** : Validation sur vrais devices obligatoire
- **Modularité** : Features indépendantes pour faciliter debug

## Workflow Type
1. **IA produit** : Code + documentation + instructions déploiement
2. **Humain teste** : Deploy + validation + feedback bugs/améliorations  
3. **IA corrige** : Iterations basées sur retours
4. **Repeat** : Cycle 2 semaines par feature

## Objectif Immédiat
Setup infrastructure complète et premier backend fonctionnel avec authentification basique.