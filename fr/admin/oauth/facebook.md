### Enregistrer et configurer une App Facebook
---

<p style="color: red">Ajouter les captures d'écran !!!</p>

Connectez-vous à Facebook

Aller à Facebook Developers Apps. Vous avez besoin d'un compte Facebook Développeur pour démarrer. Si vous n'en avez pas, mettez votre compte Facebook personnel à jour vers un compte Facebook Développeur.

Cliquez sur le bouton ou utilisez le menu déroulant et choisissez **Create a New App**.

Choisissez **Basic setup** lorsqu'on vous demande de choisir une plateforme.

Donnez un nom à votre app, choisissez Apps comme **Catégorie** et cliquez pour créer un ID d'App.

Complétez le **Security Check**.

Votre App est créée à présent! Copiez l'ID de l'App et le Secret de l'App du tableau de bord et copiez-les dans Claroline: Administration -> Paramètres de la platforme -> Oauth -> Facebook. Remplissez les champs **ID de l'application" et "Secret de l'application".

Configurez à présent votre App. Allez dans les **Paramètres", donnez un courriel valide dans l'onglet "Basic" et cliquez sur "Save".

Allez dans l'onglet **Advanced** et sélectionnez **Client OAuth Settings**. Choisissez l'option **Embedded Browser OAuth Login** et pour le **Valid OAuth redirect URL**, écrivez votre URL sous la forme suivante: _http://YOUR_DOMAIN_NAME/login/check-facebook_

_Exemple: http://3l.claroline.com/login/check-facebook_

![](/fr/admin/oauth/images/fb_app_enable_browser_add_redirect.jpg)

Allez sur **App Review** et à la question _"Do you want to make this app and all its live features available to the general public?"_, répondez **Yes* de façon à publier votre App.

Félicitations! Vous avez configuré votre App Facebook!