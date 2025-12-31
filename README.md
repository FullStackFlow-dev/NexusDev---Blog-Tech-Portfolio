# NexusDev - Blog Tech & Portfolio

![Project Status](https://img.shields.io/badge/Status-En%20D%C3%A9veloppement-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Netlify](https://img.shields.io/badge/Netlify-Deployed-success?style=for-the-badge&logo=netlify)

Une plateforme de blogging et portfolio axée sur le HTML/CSS/Vanilla JS — responsive, accessible et performante.

Demo: https://merphdev-portfolio.netlify.app/

## Aperçu rapide

- HTML sémantique (article, nav, aside)
- CSS moderne (variables, Grid, Flexbox)
- Vanilla JS: rendu d'articles depuis `data/articles.json`, filtrage par catégorie, menu hamburger, mode sombre
- Accessible: navigation clavier, attributs ARIA, focus visible

## Structure suggérée
- index.html
- css/styles.css
- js/main.js
- data/articles.json
- assets/images/...

## Installation & démarrage local

Option 1 — ouvrir localement (méthode simple)
1. Cloner :
   git clone https://github.com/FullStackFlow-dev/NexusDev---Blog-Tech-Portfolio.git
2. Aller dans le dossier :
   cd NexusDev---Blog-Tech-Portfolio
3. Ouvrir `index.html` dans le navigateur (ou utiliser l’extension Live Server de VS Code).

Option 2 — serveur local via Node (recommandé)
1. Installer Node/npm si nécessaire
2. (optionnel) npm install
3. npm run start
4. Ouvrir http://localhost:8080

## Ajouter un article
Ajouter un objet dans `data/articles.json` :
{
  "id": "slug",
  "title": "Titre",
  "date": "2025-12-29",
  "category": "Frontend",
  "summary": "Résumé",
  "content": "Contenu en HTML ou excerpt",
  "image": "assets/images/monimage.jpg"
}

## Contribuer
Voir CONTRIBUTING.md et .github/ISSUE_TEMPLATE pour ouvrir une issue ou PR.

## Licence
MIT — voir LICENSE.