# Site vitrine Jikke

Site statique (HTML + CSS), sans JavaScript, sans cookie, sans pisteur, sans police ni service externe.

## Contenu
- `index.html` : page d'accueil
- `supprimer-mon-compte.html` : page exigée par Google Play
- `css/style.css` : styles
- `fonts/` : polices Andika et Bricolage Grotesque, hébergées sur le site
- `img/` : captures de l'application (WebP), image d'aperçu de la vidéo, image de partage `partage.jpg` (1200×630)
- `video/jikke-on-me-doit.mp4` : vidéo (0,7 Mo), chargée seulement au clic

## Publier sur GitHub Pages
1. Créez un dépôt **public** nommé `jikke-site` (le nom `jikke` est déjà pris par le dépôt privé de l'application), et mettez-y tout le contenu de ce dossier (à la racine).
2. Dans le dépôt : Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Le site sera en ligne à l'adresse `https://boubacarsi.github.io/jikke-site/`.

## Nom de domaine (plus tard)
1. Achetez le domaine chez un registraire.
2. Dans Settings > Pages > Custom domain, entrez le domaine (GitHub crée le fichier `CNAME`), puis cochez « Enforce HTTPS ».
3. Chez le registraire, ajoutez les enregistrements DNS indiqués par GitHub.
4. Remplacez `https://boubacarsi.github.io/jikke-site/` par la nouvelle adresse dans les balises `canonical` et `og:` des deux pages.

## Au lancement sur Google Play
Le bouton « Rejoindre le pilote » apparaît 3 fois dans `index.html` (commentaires `BOUTON D'ACTION 1/3, 2/3, 3/3`).
Remplacez le lien `https://wa.me/224624013003?...` par le lien de la fiche Google Play
(`https://play.google.com/store/apps/details?id=VOTRE.ID.APPLICATION`) et le texte par « Disponible sur Google Play »,
ou par le badge officiel fourni par Google (https://play.google.com/intl/fr/badges/).
Pensez aussi à mettre à jour la question « Comment essayer Jikke ? » dans la FAQ.

