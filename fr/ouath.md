## OAuth (Connexion via les réseaux sociaux)
---


Provides a plugin for Claroline Connect platform that ennables users to connect through social login (facebook, twitter, google, linkedin, windows live, office 365)
Plugin Activation

Make sure the Oauth plugin is activated. In Administration -> Parameters -> Plugins make sure the IcapOAuthBundle plugin is checked.
Configuration

In order to enable 3rd party connection (social login) using the OAuth service you will need to generate a pair of App key + App Secret for every provider available (for the moment facebook, twitter, google, linkedin, windows live, office 365)

Click on the following links to learn how to configure your App for every provider and eventually retrieve your App key & secret

    Facebook
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