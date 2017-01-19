## Configurer les connexions via les réseaux sociaux
---

Le plugin OAuth permet aux utilisateurs de se connecter à une plateforme Claroline Connect via les réseaux sociaux (Facebook, Twitter, Google+, LinkedIn, Windows Live et Office 365).

### Activation du plugin

Assurez-vous que le plugin OAuth est activaté. Dans Administration -> Parameters -> Plugins assurez-vous que IcapOAuthBundle est sélectionné.

### Configuration

Pour permettre la connexion par un tiers (réseaux sociaux) en utilisant le service OAuth , vous devez générer une cléf d'App et un secret d'App pour chaque fournisseur disponible. Pour l'instant, le service fonctionne avec Faccebook, Twitter, Google+, LinkedIn, Windows Live et Office 365.

Pour savoir comment générer les App pour chaque fournisseur et récupérer les clef et secret, cliquez sur les liens suivants:

[Facebook](facebook.md "Connexion via Facebook")

[Twitter](twitter.md "Connexion via Twitter")

[Google+](google.md "Connexion via Google+")

[LinkedIn](linkedin.md "Connexion via LinkedIn")

[Windows Live](windows.md "Connexion via Windows Live")

[Office 365](office.md "Connexion via Office 365")


Une fois que vous avez créé votre App et obtenus vos clefs, vous pouvez permttre la connexion à votre plateforme Claroline via un fournisseur tiers.

Pour permettre une connexion via réseau social, par exemple Facebook:

* Aller sur Administration -> Paramètres de la plateforme
* Cliquer sur l'option OAuth
* Choisissez le fournisseur que vous voulez configurer (par exemple Facebook)
* Remplissez le formulaire avec votre identifiant (clef de l'App) et votre secret (secret de l'App), sélectionnez **Activer** et **Sauvegarder**.

NB: Si disponible, vous pouvez sélectionner la réauthentification de force pour demander aux utilisateurs de vérifier leur identité chaque fois qu'ils se connectent via ce fournisseur.

Votre connexion via les réseaux sociaux est à présent activée. Vous pouvez la tester sur votre par de connexion.
ATTENTION! Vous devez posséder les droits administrateur pour configurer les paramètres de la plateforme.

Si la configuration de votre App est correcte, vous devriez pouvoir vous connecter en utilisant la connexion tierce. Si ce n'est pas le cas, vérifiez la configuration de votre App et de la plateforme.

Si vous avez encore des difficultés, n'hésitez pas à nous contacter.