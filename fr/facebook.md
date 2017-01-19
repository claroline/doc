## Register and Configure a Facebook App
---

Login to Facebook

Go to Facebook Developers Apps. You'll need Facebook developer account to get started. If you don't have one just upgrade your personal Facebook account to a Facebook Developer account.

Click the Create a New App button Create App using button or via the dropdown menu My Apps choose Add a new App Create App using dropdown menu

When asked to choose a platform, select Basic setup Choose basic setup

Provide a Display Name for your app, choose Apps for pages Category, and click Create App ID App display name and category

Complete the Security Check Security check

Your App is now created! Copy the App ID and App Secret from the Dashboard page You can paste them to Claroline: Administration -> Platform Settings -> Oauth -> Facebook App ID and Secret

Now you need to configure your app. Go to Settings and in the Basic tab provide a valid Contact Email and click on Save Changes Fill contact email Go to the Advanced tab and scroll down to Client OAuth Settings. Enable the option Embedded Browser OAuth Login and in the Valid OAuth redirect URIs enter the following URL:

http://YOUR_DOMAIN_NAME/login/check-facebook

e.g. http://myclaroline.univ-lyon.fr/login/check-facebook

Last, got to App Review and set Do you want to make this app and all its live features available to the general public? option to Yes in order to publish your App Publish App

Congratulations you have now registered and configured your Facebook App!