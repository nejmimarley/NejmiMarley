# Site Web personnel — starter

Ce dépôt contient un site statique bilingue (fr/en) prêt à être publié via GitHub Pages.

Structure:
- `/` -> page d'accueil avec choix de langue
- `/fr/` -> pages en français (index.html, about.html, projects.html, experience.html, contact.html)
- `/en/` -> pages en anglais (mêmes fichiers traduits)
- `/assets/` -> styles et placeholders (remplacer par tes images et cv)
- `CNAME` -> contient le domaine personnalisé (nejmimarley.fr) PAS UTILE DE SUITE

Comment modifier le site (méthode simple):
1. Va sur GitHub dans le dépôt `nejmimarley/NejmiMarley`.
2. Clique sur un fichier (ex: `fr/index.html`) puis sur l'icône du stylo pour éditer dans l'interface web.
3. Sauvegarde les changements en bas de page (commit). Les modifications apparaitront sur le site après quelques minutes.

Publier avec GitHub Pages:
1. Dans GitHub, va dans Settings → Pages.
2. Pour "Source", choisis `main` branch et `/ (root)` puis clique sur Save.
3. GitHub commencera la publication. Le site sera accessible à `https://nejmimarley.github.io/NejmiMarley/`.

Configurer le domaine personnalisé (nejmimarley.fr):
1. J’ai inclus un fichier `CNAME` contenant `nejmimarley.fr`.
2. Dans le panneau DNS de ton registrar (là où tu as acheté nejmimarley.fr) configure:
   - 4 enregistrements A pointant vers les IP GitHub Pages:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Et pour `www` ajoute un CNAME vers `nejmimarley.github.io` (optionnel).
3. Retourne dans Settings → Pages, vérifie le domaine personnalisé et active HTTPS si proposé.
4. Attends la propagation DNS (quelques minutes à 24h) puis teste `https://nejmimarley.fr`.

Remplacer les fichiers importants:
- `/assets/profile-placeholder.png` -> remplace par ta photo (même nom ou modifie le chemin dans les pages)
- `/assets/cv.pdf` -> remplace par ton CV
- Formulaire: change l'`action` Formspree par ton endpoint ou remplace par `mailto:` si tu préfères.

Besoin d'aide:
- Si tu veux, je peux:
  - ajouter ton contenu réel (photo, CV, projets) si tu me fournis les fichiers et textes;
  - personnaliser le style (couleurs, polices);
  - ajouter analytics ou formulaire hébergé.
Merci
