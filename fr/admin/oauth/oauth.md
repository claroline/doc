## Configurer les connexions via les réseaux sociaux
---

Le plugin OAuth permet aux utilisateurs de se connecter à une plateforme Claroline Connect via les réseaux sociaux (Facebook, Twitter, Google+, LinkedIn, Windows Live et Office 365).

### Activation du plugin

Assurez-vous que le plugin OAuth est activaté. Dans Administration -> Parameters -> Plugins assurez-vous que IcapOAuthBundle est sélectionné.

### Configuration

Pour permettre la connexion par un tiers (réseaux sociaux) en utilisant le service OAuth , vous devez générer une cléf d'App et un secret d'App pour chaque fournisseur disponible. Pour l'instant, le service fonctionne avec Faccebook, Twitter, Google+, LinkedIn, Windows Live et Office 365.

Pour savoir comment générer les App pour chaque fournisseur et récupérer les clef et secret, cliquez sur les liens suivants:

[Facebook](facebook.md "Connexion via Facebook")

    Twitter
    Google
    LinkedIn
    Windows Live
    Office 365

Une fois que vous avez créé votre App et obtenus vos clefs, vous pouvez permttre la connexion à votre plateforme Claroline via un fournisseur tiers.

Pour permettre une connexion via réseau social, par exemple Facebook:

* Aller sur Administration -> Paramètres de la plateforme
* Cliquer sur l'option OAuth
* Choisissez le fournisseur que vous voulez configurer (par exemple Facebook)
* Remplissez le formulaire avec votre identifiant (clef de l'App) et votre secret (secret de l'App), sélectionnez **Activer** et **Sauvegarder**.

NB: If available you can check the force re-authentication option to ask from users to verify their identity every time they connect through this provider

Your social login is now enabled. You can test it on your login page.
ATTENTION! You need to have administration priviledges in order to set any platform parameters

If your App configuration is correct then you should be able to connect using the external login. If you encounter any issues please verify your configuration both in the App and in the platform.

If you are still having difficulty connecting through your App do not hesitate to contact us.