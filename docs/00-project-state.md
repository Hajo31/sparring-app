# État du Projet Sparring App

**Dernière mise à jour** : 20 juillet 2025  
**Phase actuelle** : Phase 0 - Setup Infrastructure  
**Progression** : 5% du projet total

## Vue d'ensemble
Application mobile de matching entre boxeurs thaïlandais pour organiser des sessions de sparring.
Approche "Tinder for boxers" avec géolocalisation et chat intégré.

## Statut Infrastructure
- **Repository** : ✅ GitHub configuré  
- **Backend** : ❌ En attente de création
- **Frontend** : ❌ En attente de création
- **Database** : ❌ MongoDB Atlas à configurer
- **Images** : ❌ Cloudinary à configurer
- **Déploiement** : ❌ Heroku à configurer

## Features Prévues (MVP)
- [ ] Authentification (email/password)
- [ ] Profils utilisateurs (nom, niveau, photo, localisation)
- [ ] Matching géolocalisé (voir boxeurs à proximité)
- [ ] Système like/pass
- [ ] Chat entre matchs
- [ ] Planification sessions (date/heure/lieu)

## Décisions Techniques Prises
- **Frontend** : React Native Expo (simplicité déploiement)
- **Backend** : Node.js + Express.js (familier)
- **Database** : MongoDB Atlas (cloud managé)
- **Images** : Cloudinary (gratuit jusqu'à limite)
- **Déploiement** : Heroku (simple pour MVP)
- **Maps** : Google Maps API
- **Push** : Expo Push Notifications

## Problèmes Actuels
*Aucun - Phase setup*

## Risques Identifiés
1. **Technique** : Complexité géolocalisation temps réel
2. **Adoption** : Besoin masse critique d'utilisateurs
3. **Budget** : Coûts APIs si succès rapide

## Métriques de Succès MVP
- Application stable sans crash
- 20-50 beta testeurs actifs
- 5-10 sessions de sparring organisées via l'app
- Feedback utilisateur > 4/5

## Budget Actuel
- **Développement** : 0€ (collaboration)
- **Infrastructure** : 0-50€/mois estimé
- **Services** : Apple Dev (99€/an), Google Play (25€)

## Prochaines Milestones
1. **Setup complet** (semaine 1-2)
2. **Backend + Auth** (semaine 3-4) 
3. **Frontend basique** (semaine 5-6)
4. **MVP fonctionnel** (mois 3-4)