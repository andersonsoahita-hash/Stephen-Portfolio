# Stephen Anderson Soahita · site recruteur

Version courte et orientée recruteur du site personnel. Site statique (HTML, CSS, JS), rien à installer.
Créée à partir de `Stephen-Brand`, sans Stephen Group, applications, livres, ni détails personnels.

## À vérifier dans `index.html` (bloc `SOCIAL`, juste après `const ROWS`)
- **Facebook** : l'adresse est renseignée ; précise le texte (`handle`, `txt`) selon que c'est ta page ou celle de Speak Up.
- **CV** : mets le PDF dans un dossier `cv/` et indique son chemin dans `cv:` (vide = bouton masqué).
- **Chiffres** : `STATS` et `STATS_NOTE` (page d'accueil) à mettre à jour avant chaque envoi.

## Publier sur GitHub Pages
1. Créer un nouveau dépôt (par ex. `stephen-recruteur`).
2. Envoyer `index.html`, `img/` et `.nojekyll` à la racine.
3. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.

## Moteurs de recherche
La page contient `<meta name="robots" content="noindex,nofollow">` : Google ne l'indexe pas.
Pour être trouvé en cherchant ton nom, remplace par `index,follow`.
