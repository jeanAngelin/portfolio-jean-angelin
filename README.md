# Portfolio — Jean Angelin ANDRIAMANANTENA

Portfolio personnel en HTML, CSS et JavaScript, sans dépendance ni étape de compilation. La page d’entrée est `index.html` et les images, le CV et le rapport PDF se trouvent dans `assets/`.

## Publier sur GitHub

1. Connectez-vous à [GitHub](https://github.com) et créez un dépôt nommé `portfolio-jean-angelin`.
2. Pour suivre cette méthode dans le navigateur, créez le dépôt vide : ne cochez pas les options d’ajout automatique d’un README, d’une licence ou d’un `.gitignore`.
3. Dans le dépôt, choisissez **Add file > Upload files**.
4. Depuis ce dossier du portfolio, faites glisser `index.html`, `README.md` et le dossier `assets` dans la zone de dépôt. Vérifiez que les fichiers du dossier `assets` sont bien inclus.
5. Ajoutez un message, par exemple `Publier le portfolio`, puis cliquez sur **Commit changes**.

Le dépôt contient alors les fichiers du site. Gardez-le public si vous voulez que le code soit visible publiquement ; le site Netlify pourra être public même si le dépôt est privé, selon les réglages de votre compte.

## Déployer gratuitement sur Netlify

La connexion GitHub permet à Netlify de republier le site après chaque modification envoyée au dépôt. Le portfolio est statique : aucun framework, aucune commande de compilation et aucune fonction serveur ne sont nécessaires.

1. Créez ou ouvrez un compte sur [Netlify](https://app.netlify.com/).
2. Dans le tableau de bord, choisissez **Add new project > Import an existing project**.
3. Sélectionnez **GitHub**, autorisez Netlify à accéder au dépôt du portfolio, puis choisissez le dépôt `portfolio-jean-angelin`.
4. Pour les paramètres de publication, laissez le champ de commande de compilation vide et indiquez `.` comme répertoire de publication (la racine du dépôt où se trouve `index.html`).
5. Cliquez sur **Deploy** / **Publish**. Netlify fournit une adresse se terminant par `netlify.app` ; ouvrez-la pour vérifier la page, les images, le CV et les liens.
6. Pour les prochaines mises à jour, envoyez les nouveaux fichiers dans GitHub : Netlify lancera automatiquement une nouvelle publication.

Les libellés peuvent varier légèrement selon la langue de l’interface. Consultez les guides officiels : [déployer depuis un dépôt](https://docs.netlify.com/start/quickstarts/deploy-from-repository/) et [publier un site](https://docs.netlify.com/deploy/create-deploys/).
