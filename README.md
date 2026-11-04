# Portfolio professionnel — Yao Amoin Bodice

Portfolio personnel consacré à mon parcours et à mes apprentissages en cybersécurité, réseaux et systèmes.

## Aperçu

- **Profil :** étudiante en Master 2 Cybersécurité & Internet des objets — Université Virtuelle de Côte d’Ivoire.
- **Projet principal :** ORYVAN NEX, laboratoire personnel en cours de préparation et de déploiement.
- **Technologies du site :** HTML5, CSS3 et JavaScript natif.
- **Hébergement prévu :** GitHub Pages.

## Structure

```text
.
├── index.html
├── about.html
├── projects.html
├── oryvan-nex.html
├── learning.html
├── blog.html
├── contact.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   ├── docs/       # CV PDF et documents publics à ajouter
│   └── images/     # Images et schémas à ajouter
└── README.md
```

## Lancer en local

Le site est statique : ouvrir `index.html` dans un navigateur ou lancer un serveur local depuis la racine :

```bash
python -m http.server 8000
``

Puis ouvrir http://localhost:8000.

## Publication sur GitHub Pages

1. Ouvrir **Settings → Pages** dans ce dépôt.
2. Dans **Build and deployment**, choisir **Deploy from a branch**.
3. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.
4. Attendre la fin du déploiement et ouvrir l’URL fournie par GitHub Pages.

Le dépôt est actuellement **privé**. GitHub Pages est disponible pour les dépôts publics avec GitHub Free ; la publication depuis un dépôt privé nécessite un plan compatible (Pro, Team ou Enterprise). Un site Pages publié est accessible publiquement par défaut selon la configuration. Avant de rendre le dépôt public, vérifier qu’il ne contient aucun secret, identifiant, adresse privée, capture sensible ou document confidentiel. La visibilité du dépôt n’a pas été modifiée.

## Personnalisation à effectuer

- [ ] Ajouter une adresse e-mail professionnelle.
- [ ] Ajouter l’URL exacte du profil LinkedIn.
- [ ] Ajouter le CV PDF après relecture.
- [ ] Ajouter les dates exactes des formations et certifications vérifiables.
- [ ] Ajouter des captures, schémas et comptes rendus issus des projets réellement réalisés.
- [ ] Mettre à jour le statut ORYVAN NEX uniquement après validation des étapes et des tests.

## Fiabilité des informations

Les éléments marqués « À compléter », « À documenter » ou « À valider » sont des emplacements prévus pour les futures mises à jour. Aucun résultat de laboratoire, certification ou expérience professionnelle non confirmé n'est présenté comme acquis.

## Maintenance

Le site utilise des chemins relatifs afin de fonctionner à la racine du dépôt GitHub Pages. Les styles sont centralisés dans `assets/css/style.css` et le comportement du menu dans `assets/js/main.js`.

---
© 2026 Yao Amoin Bodice.
