# vitrine-cecile

Site vitrine pour Cécile ROGER — ostéopathe D.O. à Sion-les-Mines (44590).

## Contenu du dépôt
- `index.html` — page principale du site (site statique, Tailwind via CDN et icônes Font Awesome).

## Description
Ce dépôt contient une petite vitrine statique destinée à présenter les services, les informations pratiques et un lien de réservation en ligne (Doctolib) pour Cécile ROGER.

Lien Doctolib (prise de RDV) :
https://www.doctolib.fr/osteopathe/sion-les-mines/cecile-roger-erce-en-lamee

## Prévisualiser localement
Ouvrez simplement le fichier `index.html` dans votre navigateur (aucun build requis) :

1. Depuis l'interface de votre éditeur, double-cliquez sur `index.html`.
2. Ou depuis la racine du projet, lancez un serveur HTTP simple si vous voulez tester les ressources via localhost :

```bash
# depuis la racine du repo
python3 -m http.server 8000
# puis ouvrez http://localhost:8000
```

## Déploiement — GitHub Pages
Option simple :

1. Poussez vos modifications sur la branche `main`.
2. Dans les paramètres du dépôt GitHub (Settings → Pages), choisissez la branche `main` et le dossier `/ (root)` comme source, puis enregistrez.
3. L'URL publique sera indiquée dans la même page après quelques minutes.

Option automatique (CI) : vous pouvez ajouter un workflow GitHub Actions pour déployer sur `gh-pages` si vous préférez un process automatisé.

## Modifier le site
- Éditez `index.html` pour mettre à jour le contenu, les horaires, les images ou les liens.
- Les changements sont statiques ; une fois poussés, ils seront visibles sur GitHub Pages si configuré.

## Contact / maintenance
Pour toute modification particulière (images, mentions légales, formulaire), commitez vos changements sur `main` et activez GitHub Pages comme indiqué ci‑dessus.

---
Fichier généré / mis à jour automatiquement depuis l'espace de travail.
