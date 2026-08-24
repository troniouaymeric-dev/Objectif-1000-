# Objectif 1000 — Foot Bankroll Tracker V1.1 (PWA)

Cette version peut être installée comme une application sur Android/iPhone une fois hébergée en HTTPS.

## Mise en ligne simple avec GitHub Pages
1. Créer un dépôt GitHub, par exemple `objectif-1000`.
2. Envoyer tous les fichiers de ce dossier à la racine du dépôt.
3. GitHub → Settings → Pages.
4. Dans "Build and deployment", choisir "Deploy from a branch".
5. Branch : `main`, dossier : `/ (root)`, puis Save.
6. Attendre la publication et ouvrir l'adresse GitHub Pages sur le téléphone.

## Installation Android / Chrome
1. Ouvrir l'adresse de l'application dans Chrome.
2. Appuyer sur le bouton "Installer l’app" s'il apparaît.
3. Sinon : menu ⋮ → "Ajouter à l'écran d'accueil" ou "Installer l'application".
4. L'icône "Objectif 1000" apparaîtra sur l'écran d'accueil.

## Données
Les paris restent enregistrés dans le stockage local du navigateur/appareil.
Utiliser régulièrement "Exporter JSON" pour conserver une sauvegarde.


## V1.2
- Ajout d’un bouton « 📸 Ajouter par capture ».
- OCR local dans le navigateur avec Tesseract.js.
- Pré-remplissage de la mise, cote totale, retour, statut et sélections détectées.
- Écran de validation avant enregistrement.
- Correction des chemins d’icônes pour un dépôt GitHub Pages avec fichiers à la racine.

> Limite : l’OCR local peut faire des erreurs selon la capture. La validation reste recommandée. Une version ultérieure avec analyse visuelle serveur peut être plus fiable.

## V1.3
- Choix d'une ou plusieurs captures directement depuis la galerie.
- Bouton séparé pour utiliser l'appareil photo.
- Plusieurs screenshots peuvent être analysés pour un même combiné.
- Les textes OCR sont fusionnés avant la détection du pari.


## V2
- OCR général + zones Betclic ciblées.
- Prétraitement contraste/agrandissement.
- Détection renforcée mise, gains, cote, équipes, score, type et date.
- Écran de validation conservé.
