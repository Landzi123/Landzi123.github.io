# Portfolio — Alexandre Lartigue

Portfolio personnel : étudiant ingénieur en 4ème année à l'ESILV, spécialisé en Data Science et Intelligence Artificielle. Le site présente mes projets, organisés par thématique, avec pour chacun une image, un résumé et un lien vers le dépôt GitHub associé.

**Site en ligne :** https://landzi123.github.io

## Sections

- **Data** — traitement de données, analyse et modèles prédictifs.
- **IA & Automatisation** — agents IA et workflows n8n.
- **Développement logiciel** — applications, algorithmes et bases de données.

## Structure du dépôt
.
├── index.html # page unique du portfolio (HTML/CSS/JS autonome)
└── images/ # images des projets

## Ajouter ou modifier un projet

Tout le contenu (sections et projets) est défini dans le bloc `SECTIONS` en haut du `<script>` de `index.html`. Pour chaque projet :

- `title`, `summary`, `highlights`, `stack` : texte affiché sur la fiche projet.
- `image` : chemin de l'image dans `images/` (ex. `"images/mon-projet.webp"`).
- `github` : lien vers le dépôt GitHub du projet.

Il suffit de copier un bloc de projet existant, de le modifier, et de déposer l'image correspondante dans `images/`.

## Technologies

HTML, CSS et JavaScript natifs — aucune dépendance, aucune étape de build. Le site fonctionne comme une page statique unique, compatible avec GitHub Pages.
