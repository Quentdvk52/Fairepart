# Guide d'Utilisation des Fichiers Locaux

## Structure des Dossiers

```
obseques-site/
├── assets/
│   ├── images/
│   │   ├── hero.jpg          # Photo principale
│   │   ├── couple.jpg        # Photo du couple
│   │   ├── lozenge.jpg       # Photo en cadre losange
│   │   ├── tissue.jpg        # Photo des tissus
│   │   ├── souvenir1.jpg     # Photo souvenir 1
│   │   └── souvenir2.jpg     # Photo souvenir 2
│   ├── audio/
│   │   ├── main.mp3          # Musique principale
│   │   └── thanks.mp3        # Musique de remerciements
│   ├── config.js             # Configuration JavaScript
│   └── media-data.json       # Données des médias
├── index.html
└── README.md
```

## Comment Ajouter Vos Fichiers

### 1. Télécharger les fichiers depuis Google Drive

1. Allez sur chaque lien Google Drive fourni
2. Téléchargez le fichier sur votre ordinateur
3. Renommez-le selon le nom correspondant dans la structure ci-dessus
4. Placez-le dans le dossier approprié (`assets/images/` ou `assets/audio/`)

### 2. Fichiers Images Requis

- **hero.jpg** : Photo principale de la défunte
- **couple.jpg** : Photo du couple HOUNNONGAN DASSOU
- **lozenge.jpg** : Photo pour le cadre losange
- **tissue.jpg** : Photo des tissus de la cérémonie
- **souvenir1.jpg** : Photo souvenir 1
- **souvenir2.jpg** : Photo souvenir 2

### 3. Fichiers Audio Requis

- **main.mp3** : Musique de recueillement (auto-play)
- **thanks.mp3** : Musique de remerciements

## Configuration

Le site utilise un système de **fallback automatique** :

1. **Priorité** : Il cherche d'abord les fichiers locaux dans `assets/`
2. **Fallback** : Si le fichier local n'existe pas, il utilise les liens Google Drive

Vous n'avez rien à modifier dans le code - ajoutez simplement vos fichiers dans les dossiers et ils seront automatiquement utilisés.

## Liens Google Drive (pour téléchargement)

### Images
- Hero : https://drive.google.com/file/d/1hm5p-r8_5oCRK5LLi9kwFw1o8fkGVOxv/view
- Couple : https://drive.google.com/file/d/1xeYL4PuEpE8dlVx9MVG-OWB7diWHxwLi/view
- Lozenge : https://drive.google.com/file/d/1cx6CWk7WPeSOHl6_Iv13kTslJnUO9l88/view
- Tissue : https://drive.google.com/file/d/1DQeTTEIEUvRJz7xKPzD_UaZ0MUMcTvec/view
- Souvenir 1 : https://drive.google.com/file/d/1Q-1Gwu2AU_wVTxRsYmjCDSTGqRi9xi_C/view
- Souvenir 2 : https://drive.google.com/file/d/10I7eb3aeyKeBK4rHXnXZt6oq5_QVEk_R/view

### Audio
- Main : https://drive.google.com/file/d/16ESxve26XfHgOWCIqTbwxDbqUGcoav4V/view
- Thanks : https://drive.google.com/file/d/1zBofUo6qvgaTXTuY6MZ45rgei5Oaqv6G/view

## Recommandations pour les Fichiers

### Images
- **Format** : JPG ou PNG
- **Taille** : 800-1200px de large (maximum)
- **Poids** : < 500KB par image pour optimisation
- **Compression** : Utilisez TinyPNG ou Squoosh avant l'ajout

### Audio
- **Format** : MP3
- **Qualité** : 128-192 kbps
- **Taille** : < 5MB par fichier
- **Durée** : Idéalement < 5 minutes

## Google Map

La carte utilise maintenant un embed simplifié qui devrait s'afficher correctement :
- Lieu : Cs Gnidjaszoun
- Zoom : 15
- Format : Embed Google Maps standard

## Vérification

Après avoir ajouté vos fichiers :

1. Ouvrez le site dans le navigateur
2. Vérifiez que les images s'affichent
3. Testez l'audio (auto-play + bouton play/pause)
4. Vérifiez que la carte Google Maps s'affiche
5. Testez les boutons WhatsApp

## Dépannage

### Images ne s'affichent pas
- Vérifiez que les fichiers sont dans les bons dossiers
- Vérifiez les noms de fichiers (doivent correspondre exactement)
- Les fichiers Google Drive doivent être partagés avec "Tout le monde avec le lien"

### Audio ne fonctionne pas
- Vérifiez le format du fichier (MP3 recommandé)
- Les navigateurs peuvent bloquer l'auto-play - cliquez sur le bouton play
- Testez avec différents navigateurs

### Carte ne s'affiche pas
- Vérifiez votre connexion internet
- Le lien Google Maps a été simplifié pour éviter les erreurs
- Essayez de rafraîchir la page
