# Jeu de Couple — pack PWA

Contenu :
- index.html
- manifest.json
- service-worker.js
- icons/
- .nojekyll

## Déploiement ultra simple sur GitHub Pages
1. Crée un dépôt GitHub public.
2. Envoie tous les fichiers de ce dossier à la racine du dépôt.
3. Dans GitHub > Settings > Pages :
   - Source : Deploy from a branch
   - Branch : main
   - Folder : /(root)
4. Attends l’URL du site, par exemple :
   https://toncompte.github.io/nom-du-depot/

## Conversion en APK
1. Ouvre PWABuilder.
2. Colle l’URL publique du site.
3. Vérifie que le manifest et le service worker sont détectés.
4. Génère le package Android.

## Nom de package conseillé
com.tonnom.jeudecouple
