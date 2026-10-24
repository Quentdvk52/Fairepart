# Mémo de mission — Site d'obsèques

## Objectif
Créer un site web one-page, responsive et mobile-first pour annoncer un décès et transmettre les informations pratiques aux invités aux obsèques.

## Périmètre
**Dans le périmètre :**
- Page one-page complète (HTML/CSS/JS)
- Design sobre, éditorial et intemporel
- Sections : en-tête, annonce décès, invitation cérémonie, programme, localisation avec carte, lecteur audio discret, réception/menu, contact WhatsApp, pied de page
- Responsive mobile-first (smartphone prioritaire)
- Animations légères et accessibles
- SEO de base (meta tags, accessibilité)

**Hors périmètre :**
- Base de données (contenu statique)
- Authentification
- Système de paiement
- Back-office admin
- Génération de PDF

## Décisions techniques
- Stack : HTML5 + CSS3 + JavaScript vanilla (sans framework)
- Approche : fichier unique ou structure simple avec index.html + assets
- Carte : iframe Google Maps ou OpenStreetMap (choix basé sur la simplicité)
- Audio : HTML5 audio player avec contrôles personnalisés
- Animations : CSS transitions + Intersection Observer pour le scroll
- Hébergement : fichiers statiques (Vercel, Netlify, ou GitHub Pages)

## Points de sécurité
- Pas de données sensibles à traiter (contenu public)
- Validation des entrées utilisateur si formulaire contact (à confirmer)
- HTTPS obligatoire en production

## Plan d'exécution
1. Créer la structure HTML sémantique
2. Implémenter le design CSS avec palette ivoire/beige/vert sauge
3. Intégrer les sections demandées avec placeholders
4. Ajouter les fonctionnalités interactives (audio, carte, WhatsApp)
5. Optimiser le responsive mobile-first
6. Ajouter les animations légères avec respect des préférences utilisateur
7. Vérifier l'accessibilité et le SEO

## État
- ✅ Phase 1 : Compréhension
- ✅ Phase 2 : Cadrage (mémo créé)
- ✅ Phase 3 : Exécution (site créé avec données réelles)
- ✅ Phase 4 : Vérification
- ✅ Phase 5 : Clôture

## Données réelles intégrées
- **Personne** : Kouzalode djotondagba agounha (90 ans)
- **Cérémonie** : Samedi 28 Novembre 2026 à 12h, Gnidjaszoun
- **Familles** : AZOUNHOUMIN, KAKOUDE, AKOUKPAHOUN, ABETEKOU, TOHOSSSOU AGOUNHA, DASSOU
- **Couple** : HOUNNONGAN DASSOU
- **Localisation** : Cs Gnidjaszoun (Google Maps)
- **Médias** : 
  - Photo hero (Google Drive)
  - Photo couple (Google Drive)
  - Photo losange (Google Drive)
  - Photo tissus (Google Drive)
  - 2 photos souvenir côte à côte (Google Drive)
  - Audio 1 auto-play (Google Drive)
  - Audio 2 (démarre après audio 1, Google Drive)
- **Éléments graphiques** :
  - "In Memoriam" (Great Vibes) au-dessus de la photo
  - Nom en bas à gauche de la photo
  - Bougie allumée + âge 90 ans en bas à droite
- **Sections** : Annonce de décès, Localisation, Tissus (avec bouton WhatsApp), Remerciements
- **Contact** : WhatsApp tissus (+229 96 78 53 41), WhatsApp footer (+229 01 48 49 49 06)
- **Crédit** : YEKPON DIGIT

## Livrable final
- Site one-page complet (version cinématique) : `index.html`
- Documentation de personnalisation : `README.md`
- Design system généré via ui-ux-pro-max (Brutalism Dark avec Variance 8, Motion 9)
- Skills GitHub installés globalement dans `~/.agents/skills/`

## Décisions techniques prises
- HTML5 + CSS3 + JavaScript vanilla + GSAP 3.12.2 (animations professionnelles)
- Design mobile-first avec breakpoints fluides (375px, 768px, 1024px, 1440px)
- Palette cinématique dark : noir (#000000), or (#D4AF37), gris foncés
- Typographie impactante : Bebas Neue (display) + Source Sans 3 (corps)
- Animations avancées : GSAP ScrollTrigger, Flip, parallax, stagger, reveal
- Vidéo background dans hero + section vidéo hommage + galerie photos
- Cartes Google Maps avec filtre dark mode (grayscale + invert)
- Loader animé pour expérience immersive
- Structure sémantique pour accessibilité et SEO
- Respect strict de prefers-reduced-motion
- Lecteur audio HTML5 natif
- Bouton WhatsApp avec animations hover

## Points de vérification
- ✅ Responsive mobile-first (375px, 768px, 1024px+)
- ✅ Accessibilité (keyboard, screen reader, contraste 4.5:1 minimum)
- ✅ SEO (meta tags, structure h1-h2-h3, alt text)
- ✅ Animations respectueuses (prefers-reduced-motion)
- ✅ Navigation clavier et focus visible
- ✅ Pas de dépendances externes (sauf Google Fonts et cartes)
- ✅ Code propre et commenté
