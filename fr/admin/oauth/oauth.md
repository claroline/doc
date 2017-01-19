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

Once you've created your App and got your keys, it's time to enable login to your Claroline platform.

To enable your social login, let's say facebook login for example:

    Head over to Administration -> Platform parameters
    Click on Oauth option
    Choose the provider you wish to enable/configure (e.g. facebook)
    Fill in the form with your application id (App key) and your secret (App secret), check activate and then save

NB: If available you can check the force re-authentication option to ask from users to verify their identity every time they connect through this provider

Your social login is now enabled. You can test it on your login page.
ATTENTION! You need to have administration priviledges in order to set any platform parameters

If your App configuration is correct then you should be able to connect using the external login. If you encounter any issues please verify your configuration both in the App and in the platform.

If you are still having difficulty connecting through your App do not hesitate to contact us.