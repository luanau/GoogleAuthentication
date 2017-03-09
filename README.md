# GoogleAuthentication

The **Authorised redirect URIs** in the google app credentials must be set to https://localhost:44341/signin-google (just append signin-google to the home page)

> You don't need to configure signin-google as a route in your app. The Google middleware automatically intercepts requests at this route and handles them to implement the OAuth flow.


