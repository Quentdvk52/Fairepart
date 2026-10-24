# Site d'Obsèques - Kouzalode djotondagba agounha

Site web one-page, responsive et mobile-first pour les obsèques de Kouzalode djotondagba agounha.

## 🎬 Caractéristiques

- ✅ **Menu de bas de page mobile** avec 5 sections
- ✅ **"In Memoriam"** en police Great Vibes au-dessus de la photo
- ✅ **Photo hero** avec nom en bas à gauche
- ✅ **Bougie allumée** avec flamme animée et âge (90 ans) en bas à droite
- ✅ **Lecteur audio auto-play** dès l'arrivée sur le site
- ✅ **Annonce de décès** avec liste des familles
- ✅ **Photo du couple** HOUNNONGAN DASSOU
- ✅ **Photo en cadre losange doré**
- ✅ **Localisation Google Maps** de Gnidjaszoun
- ✅ **Section tissus** avec bouton Commander (WhatsApp)
- ✅ **Deuxième lecteur audio** qui démarre après la fin du premier
- ✅ **Deux photos côte à côte**
- ✅ **Remerciements** avec grand "Merci" en police artistique
- ✅ **Footer** avec crédit YEKPON DIGIT et bouton Commander

## 📱 Navigation

### Mobile (< 768px)
- Menu de bas de page fixe avec 5 icônes
- Accueil, Annonce, Lieu, Tissus, Merci

### Desktop (> 768px)
- Header fixe en haut avec navigation
- Menu horizontal classique

## 🎨 Sections

### 1. Hero Section
- **Titre** : "In Memoriam" (Great Vibes, doré)
- **Photo** : Photo de la défunte (Google Drive)
- **Nom** : Kouzalode djotondagba agounha (en bas à gauche)
- **Bougie + Âge** : Bougie animée + badge 90 ANS (en bas à droite)

### 2. Lecteur Audio 1
- **Auto-play** : Démarre automatiquement après 2 secondes
- **Bouton** : Play/Pause avec visualiseur
- **Fichier** : Google Drive (ID: 16ESxve26XfHgOWCIqTbwxDbqUGcoav4V)

### 3. Annonce de Décès
- **Titre** : "Annonce de décès" (police artistique)
- **Familles** :
  - Collectivité AZOUNHOUMIN de Sèhouè et de Gnidjaszoun
  - Famille KAKOUDE de Gnidjaszoun
  - Famille AKOUKPAHOUN de Gnidjaszoun
  - Famille ABETEKOU de Gnidjaszoun
  - Famille TOHOSSSOU AGOUNHA de Gnidjaszoun
  - Famille DASSOU de Dokpa Tohizanli
- **Titre couple** : "Le Couple HOUNNONGAN DASSOU"
- **Photo couple** : Google Drive (ID: 1xeYL4PuEpE8dlVx9MVG-OWB7diWHxwLi)
- **Texte invitation** : Avec nom en évidence

### 4. Photo Losange
- **Cadre** : Losange doré avec bordure rotative
- **Photo** : Google Drive (ID: 1cx6CWk7WPeSOHl6_Iv13kTslJnUO9l88)

### 5. Localisation
- **Carte** : Google Maps embed de Gnidjaszoun
- **Texte** : "Suivre cette localisation pour venir directement au lieu des cérémonies"

### 6. Tissus
- **Titre** : "Tissus de la cérémonie"
- **Photo** : Google Drive (ID: 1DQeTTEIEUvRJz7xKPzD_UaZ0MUMcTvec)
- **Bouton** : Commander → WhatsApp +229 96 78 53 41

### 7. Remerciements
- **Titre** : "Remerciements"
- **Lecteur audio 2** : Démarre automatiquement après la fin de l'audio 1
- **Deux photos** : Côte à côte (grille responsive)
- **Texte** : Message de gratitude complet
- **Grand Merci** : En police Great Vibes, doré

### 8. Footer
- **Crédit** : "Réalisé par YEKPON DIGIT"
- **Bouton** : Commander → WhatsApp +229 01 48 49 49 06

## 🎨 Design

### Couleurs
- Noir : #000000 (fond principal)
- Or : #D4AF37 (accent, titres, bordures)
- Gris foncé : #1A1A1A (sections secondaires)

### Polices
- **Great Vibes** : "In Memoriam", "Merci" (script artistique)
- **Bebas Neue** : Titres, noms (display)
- **Source Sans 3** : Corps de texte (body)

### Animations
- Loader animé
- Hero reveal séquentiel
- Scroll reveal pour chaque section
- Flamme de bougie flicker
- Visualiseur audio animé

## 📝 Personnalisation

### Changer les photos
Remplacez les URLs Google Drive par vos propres URLs :

```html
<!-- Photo hero -->
<img src="https://drive.google.com/uc?export=view&id=VOTRE_ID" alt="...">

<!-- Photo couple -->
<img src="https://drive.google.com/uc?export=view&id=VOTRE_ID" alt="...">
```

### Changer l'âge
```html
<span class="age-number">VOTRE_AGE</span>
```

### Changer les numéros WhatsApp
```html
<!-- Tissus -->
<a href="https://wa.me/229VOTRE_NUMERO">

<!-- Footer -->
<a href="https://wa.me/229VOTRE_NUMERO">
```

### Modifier le texte de l'annonce
```html
<div class="annonce-families">
    Vos familles ici...
</div>
```

### Changer la localisation
Remplacez l'URL de l'iframe Google Maps par la nouvelle localisation.

## 🚀 Déploiement

### GitHub Pages
1. Créez un repository sur GitHub
2. Uploadez `index.html`
3. Settings > Pages > Activez sur branche main

### Netlify
1. Glissez-déposez le dossier sur Netlify
2. Déploiement instantané

### Vercel
1. Importez le projet sur Vercel
2. Déployez en un clic

## 🧪 Checklist Avant Publication

- [ ] Vérifier sur mobile (menu bas de page)
- [ ] Vérifier sur desktop (header)
- [ ] Tester l'auto-play audio
- [ ] Vérifier la transition audio 1 → audio 2
- [ ] Tester les boutons WhatsApp
- [ ] Vérifier la carte Google Maps
- [ ] Tester les animations
- [ ] Vérifier le responsive (photos côte à côte)
- [ ] Contrôler le contraste des couleurs

## 💡 Notes

### Auto-play Audio
Les navigateurs modernes peuvent bloquer l'auto-play. Le code tente de lancer automatiquement, mais si bloqué, l'utilisateur peut cliquer sur le bouton play.

### Photos Google Drive
Les URLs utilisent le format `uc?export=view&id=` pour un affichage direct. Assurez-vous que les fichiers sont partagés avec "Tout le monde avec le lien".

### WhatsApp
Les numéros sont au format international sans le + (ex: 229 pour le Bénin).

## 📄 Licence

Ce projet est fourni tel quel pour un usage personnel.
