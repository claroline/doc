## Aperçu des paramètres modifiables sur la plateforme
---
En tant qu'administrateur, vous avez accès aux paramètres de votre plateforme.

![parametres.png](http://www.claroline.net/uploads/custom/images/parametres.png)

<p style="text-align: center; color: blue">Figure 35 - Accéder aux paramètres de la plateforme</p>

Voici un aperçu de ce que vous pouvez gérer.

| Outils du menu | Ce que les outils permettent |
| -- | -- |
| Général | Définir les paramètres principaux de la plateforme : nom, description de la plateforme, courriel du support, rôle par défaut, langue par défaut, durée d'activation des comptes et de la plateforme, l'auto-inscription des utilisateurs, activer ou désactiver les notifications et le bouton d'aide (qui redirige vers ce manuel d'utilisation). |
| Apparence | Modifier le thème de la plateforme (couleurs, logo, pied de page, etc.) |
| Conditions d'utilisation | Ajouter des conditions d'utilisation à valider lors de l'inscription. |
| Courriel du support | Paramétrer le courriel vers lequel les messages sont envoyés par la plateforme. |
| Référencement | Ajouter la balise HTML de validation Google qui permet le positionnement et la visibilité du site dans des pages de résultats des moteurs de recherche. |
| Session | Définir le type de stockage et la durée de vie du cookie. |
| Oauth | Paramétrer les accès aux informations en provenance d'autres plateformes (Facebook par exemple). |
| Maintenance | Passer la plateforme en **mode maintenance**. Le passage en mode maintenance rend votre plateforme indisponible le temps d'effectuer les travaux nécessaires (mises à jour, sauvegardes, etc). Toute tentative de connexion aboutira à un encadré indiquant que la plateforme est momentanément indisponible. Il conviendra donc de prévenir les utilisateurs avant de procéder à une interruption des services, de façon à éviter que des parcours ou exercices en cours d'exécution ne soient perdus. L'idéal est de prévoir un créneau de maintenance régulier (par exemple hebdomadaire).<br/> Techniquement, le passage en mode maintenance génère un fichier nommé .update dans le répertoire app/config/. <br/>**Pour sortir du mode maintenance, il faudra accéder au serveur au moyen d'un client ftp comme Filezilla, et supprimer ledit fichier.** |
| Gestion de jetons d'authentification | Vous pouvez créer un jeton d'authentification qui pourrait être utilisé, plus tard, par un développeur pour sécuriser l'authentification de la plateforme pour une application tierce. |
| i18n ou Gestion de langues | Permet de gérer les langues disponibles sur la plateforme. |
