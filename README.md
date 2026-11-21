# Atlas Bercy — Fiche pratique de catalogage

Documentation et kit d'embarquement pour le catalogage des données des ministères économiques et financiers (MEF).

## Contenu

- `index.html` : page de rendu DSFR de la fiche pratique.
- `css/custom.css` : styles complémentaires au DSFR.
- `docs/accompagnement/fiche-pratique-catalogage.md` : contenu Markdown de la fiche pratique.
- `docs/accompagnement/kit-embarquement/` : ressources du kit d'embarquement (`guide-local.md`, `mail-onboarding.md`).
- `.github/workflows/deploy.yml` : déploiement GitHub Pages.

## Aperçu local

Le chargement du Markdown utilise `fetch()`, il faut donc servir le dossier via HTTP :

```bash
python3 -m http.server 8000
```
