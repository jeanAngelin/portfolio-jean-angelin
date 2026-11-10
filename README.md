# Portfolio — Jean Angelin ANDRIAMANANTENA

Portfolio personnel en HTML, CSS et JavaScript, sans dépendance ni étape de compilation. La page d’entrée est `index.html` et les images, le CV et le rapport PDF se trouvent dans `assets/`.

## Mettre à jour le dépôt GitHub existant

Le dépôt du site est `jeanAngelin/portfolio-jean-angelin`. Pour ajouter les pages de projet depuis le site GitHub sans envoyer un dossier entier :

1. À la racine du dépôt, choisissez **Add file > Upload files** et sélectionnez les nouveaux `index.html` et `README.md` depuis ce dossier. Validez avec **Commit changes**.
2. Ouvrez le dossier `assets` dans le dépôt, choisissez **Add file > Upload files**, puis envoyez `assets/projet.css` depuis le dossier local `assets`. Validez le commit.
3. À la racine du dépôt, choisissez **Add file > Create new file**. Dans le nom du fichier, saisissez `projets/.gitkeep`, puis validez le commit pour créer le dossier.
4. Ouvrez le dossier `projets` désormais visible, choisissez **Add file > Upload files**, sélectionnez les cinq fichiers HTML du dossier local `projets`, puis validez le commit.
5. Vérifiez que le dépôt contient bien `index.html`, `assets/projet.css` et les cinq pages dans `projets/`.

## Publier les mises à jour sur Netlify

Le portfolio est statique : aucun framework, aucune commande de compilation et aucune fonction serveur ne sont nécessaires.

Si le site Netlify est relié à GitHub, chaque commit sur le dépôt déclenche automatiquement une nouvelle publication. Si ce n’est pas encore le cas, dans Netlify ouvrez le site, puis **Project configuration > Developer settings > Continuous deployment > Repository > Link repository**. Choisissez GitHub et le dépôt `portfolio-jean-angelin` ; laissez la commande de compilation vide et le répertoire de publication à `.`.

Pour une publication manuelle, ouvrez le site dans Netlify, allez dans **Deploys**, puis déposez le dossier local complet du portfolio dans la zone de publication. Le dossier doit contenir `index.html`, `assets/` et `projets/`.

Consultez les guides officiels : [relier un dépôt Git](https://docs.netlify.com/build/git-workflows/repo-permissions-linking/) et [publier des fichiers manuellement](https://docs.netlify.com/start/quickstarts/netlify-drop-quickstart/).
