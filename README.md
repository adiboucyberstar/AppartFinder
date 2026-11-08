# Apartment Finder

Application web statique gratuite pour comparer des annonces de location.

## Mise en ligne gratuite (GitHub Pages)
1. Crée un compte GitHub si tu n'en as pas, puis un nouveau dépôt public nommé `apartment-finder`.
2. Décompresse cette archive et envoie les fichiers `index.html`, `manifest.json` et `sw.js` à la racine du dépôt.
3. Dans le dépôt : Settings > Pages > Deploy from a branch > `main` > `/ (root)` > Save.
4. GitHub affichera une adresse du type `https://TON-PSEUDO.github.io/apartment-finder/`.
5. Ouvre cette adresse sur ton téléphone et utilise « Ajouter à l'écran d'accueil » depuis le menu de partage du navigateur.

## Données et confidentialité
- Aucun compte ni serveur de données n'est utilisé.
- Les annonces sont stockées dans le navigateur de l'appareil (localStorage).
- Les données ne se synchronisent pas entre téléphone et ordinateur.
- Utilise « Exporter mes données » pour faire une sauvegarde JSON, puis « Importer une sauvegarde » sur un autre appareil.
- Le dépôt GitHub est public si tu utilises GitHub Pages avec un dépôt public. Les annonces que tu saisis ne sont pas publiées dans le dépôt, mais toute personne ayant le lien du site peut utiliser sa propre copie. Ne saisis pas de données personnelles sensibles.

## Limites
- Les liens Leboncoin, SeLoger, PAP, etc. sont enregistrés mais leurs annonces ne sont pas extraites automatiquement.
- Le temps de trajet est saisi manuellement.
- Le score est indicatif et utilise les pondérations affichées dans l'application.
