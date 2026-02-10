# LPPP Yuwell Portfolio

Portfolio **étude graphique** Yuwell (Jiangsu Yuyue Medical Equipment) — 5 pages statiques : Présentation, Study case, Study case 2, Charte graphique, À propos. Charte couleur par gamme produit, typo Work Sans + Oswald ExtraLight, hero vidéo YouTube.

**Génération :** à la racine du repo LPPP :
```bash
python manage.py export_yuwell_static --output deploy/yuwell-portfolio
```

**Déploiement GitHub + GitLab :** voir `deploy/PUSH-YUWELL.md` (repos `LPPP_yuwell_portfolio`).

**Hébergement :** GitHub Pages, GitLab Pages, ou tout hébergeur de fichiers statiques (pas de build). Ouvrir `index.html` ou servir le dossier en HTTP.
