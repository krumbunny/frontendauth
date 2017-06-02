# \<frontendauth\>

Front End Authority site using Polymer

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Deploying to Firebase

Firebase has a free hosting service that handles the URL rewrite rules for a Polymer SPA. 
Following the [Polymer Deploy to Firebase](https://www.polymer-project.org/2.0/start/toolbox/deploy) 
instructions using the Firebase CLI:

```
$ firebase deploy
```

Deploys the application to the firebase static hosting service, once you have set up your own account.
