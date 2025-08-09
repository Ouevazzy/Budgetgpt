
# Budget v5 — Déploiement Vercel (sans terminal)

## Contenu
- `index.html` — l'app (fichier autonome)
- `manifest.webmanifest` — PWA
- `sw.js` — service worker minimal
- `vercel.json` — config Vercel (routes SPA)

## Déploiement sans CLI
1) Ouvre ton compte Vercel.
2) Clique **New Project** > **Import** puis **Drag & Drop** le dossier *ou* ce ZIP.
3) Vercel détecte un **Static Site** (pas de build). Clique **Deploy**.
4) Une URL sera créée. Ouvre-la sur iPhone, puis **Partager** > **Ajouter à l’écran d’accueil** pour installer la PWA.

## Remarques
- L’app stocke les données en **localStorage** (propres à chaque navigateur/app iOS).
- Tu peux mettre à jour en redéployant un nouveau ZIP (Vercel garde l’historique).
