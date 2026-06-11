# Flying For You × Charpentes Gardarein — Dossier maquettes

Mini-site statique présentant l'audit CRO et les maquettes « version idéale » du site charpentesgardarein.com.

## Contenu
- `index.html` — page d'accueil du dossier (présentation + liens)
- `maquettes/` — 3 maquettes HTML interactives (accueil, devis, page service)
- `annexes/` — audit PDF complet + backlog Excel
- `assets/` — miniatures

## Déployer sur GitHub Pages (2 min)
1. Créez un dépôt GitHub (ex. `gardarein-maquettes`) et poussez le contenu de ce dossier à la racine.
   ```bash
   git init && git add . && git commit -m "Dossier Gardarein"
   git branch -M main
   git remote add origin https://github.com/VOTRE-COMPTE/gardarein-maquettes.git
   git push -u origin main
   ```
2. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
3. L'URL publique s'affiche après ~1 min : `https://VOTRE-COMPTE.github.io/gardarein-maquettes/`

Astuce : pour une démo en RDV, ouvrez l'URL puis réduisez la fenêtre pour montrer le rendu mobile.
