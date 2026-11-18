# Site personnel – Mathieu Rosenbaum

Site statique (HTML + CSS, sans dépendance), prêt pour GitHub Pages.

## Mise en ligne (gratuit, ~5 minutes)

1. Créer un compte sur https://github.com (gratuit).
2. Créer un nouveau dépôt **public** nommé exactement `NOMUTILISATEUR.github.io`
   (remplacer NOMUTILISATEUR par l'identifiant GitHub).
3. Dans le dépôt : **Add file → Upload files**, glisser `index.html`, `style.css`, `.nojekyll`
   et ce `README.md`, puis **Commit changes**.
4. Le site est en ligne après une ou deux minutes à l'adresse `https://NOMUTILISATEUR.github.io`.
   (Si besoin : Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/root`.)

## Mettre à jour

Ouvrir `index.html` sur GitHub, cliquer sur l'icône crayon, modifier, puis **Commit changes**.
Pour ajouter un article, copier un bloc `<li class="pub" …>…</li>` existant dans la bonne liste
(« Preprints » ou « Published ») et modifier le numéro, le titre et la référence.
L'attribut `data-q` sert à la recherche : y mettre le titre et les co-auteurs en minuscules.
