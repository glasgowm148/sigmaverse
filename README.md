# [Sigmaverse](https://sigmaverse.io/)

Your portal to the Ergo universe.

Ergo has some amazing tech and some talented developers. However, as a decentralised and community-powered platform, it’s not always easy to know what’s going on all the time. Different people are developing different dApps and use cases, formally and informally. Connecting them to the same users and building that all-important DeFi network effect isn’t always easy.

That’s what the Sigmaverse is about. Sigmaverse is a one-stop portal to the Ergo dApp ecosystem: a place where users can find all the cool functionality that community developers are building on Ergo, all in one place.

The idea is that developers can create their apps, and then list them on Sigmaverse using GitHub.

As it becomes the default site for accessing dApps, more and more devs will add their own, making it easy to learn about new additions to the Ergo ecosystem. A search bar allows users to check for a specific type of dApp.

To include your dApp in Sigmaverse, create a new folder in applications/{dAppName}, and in this folder create a new file, `overview.md`, with the following contents and structure:


```
------
name: name of dApp
description: description of dApp
website: dApp website
logo_image: “{logotypeName}” – if you want to include this, save the image at applications/{dAppName}/{logotypeName}
preview_image: “{previewName}” – if you want to include this, save the image at applications/{dAppName}/{previewName}
appCategory: [“web” or/and “cli” or/and “desktop”]
category: 'dApps' 
------
```


## Getting started

```
yarn install
yarn build
yarn start
```