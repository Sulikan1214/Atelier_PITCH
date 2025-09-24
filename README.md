# Atelier – Pitch

Ce dossier est prêt à être **poussé sur GitHub** et publié via **GitHub Pages**.

## Contenu
- `index.html` — version servie automatiquement par GitHub Pages.
- `atelier_pitch.html` — le fichier original.
- `images/` — placez **toutes les images** référencées par la page ici (voir `images/README.txt`).
- `.nojekyll` — désactive Jekyll côté GitHub Pages.

## Étapes rapides (terminal)
```bash
# 1) Créez un dépôt vide sur GitHub (ex: atelier-pitch-site)
# 2) Placez-vous dans ce dossier :
cd atelier-pitch-site

# 3) Initialisez Git et validez
git init
git add .
git commit -m "Publication initiale de l'atelier Pitch"

# 4) Liez à GitHub et poussez
git branch -M main
git remote add origin https://github.com/VOTRE_PSEUDO/atelier-pitch-site.git
git push -u origin main
```

## Activer GitHub Pages
1. Ouvrez **Settings → Pages** dans votre dépôt GitHub.
2. **Source** : choisissez la branche `main` et le dossier `/ (root)`.
3. Enregistrez. L'URL de votre site sera affichée (ex: `https://votre_pseudo.github.io/atelier-pitch-site/`).

## Images manquantes ?
Le fichier `images/README.txt` liste les images attendues (détectées dans le HTML). Copiez ces fichiers dans `images/` avant de pousser.
