# Progressive Web Applications (PWA): Text Editor (sjb-PWA-Text-Editor)

## Description

This single-page application is a text editor that runs in the browser and meets the PWA criteria. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. It functions offline and users has the ability to download it as an application.
The application has been deployed to Heroku.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Preview

###### Deployed application's functionality

![exampleOfDeployedApp](./assets/DeployedApp.jpg)

###### Application's manifest.json file

![exampleOfDeployedAppManifestFile](./assets/DeployedAppManifestFile.jpg)

###### Application's registered service worker

![exampleOfDeployedAppRegisteredServiceWorker](./assets/RegisteredServiceWorker.jpg)

###### Application's IndexedDB storage

![exampleOfDeployedAppIndexedDBstorage](./assets/DeployedAppIndexedDBstorage.jpg)

## Installation

###### Local Installation

- Clone the repository from [Github](git@github.com:simmmmo/sjb-PWA-Text-Editor.git)
- Ensure Node.js is installed
- Install dependencies
  [express package](https://www.npmjs.com/package/express)

```bash
npm install
```

- Ensure all additional packages have been installed

- Run the below from the root directory to start client and server

```bash
npm run start
```

- Open http://localhost:3000 to view it in the browser

## Usage

###### Production Environment (Heroku)

- https://sjb-pwa-texteditor.herokuapp.com/

## Technology

- Node.js
- Express.js
- IndexedDB
- Webpacks
- Heroku

## Project Links

###### Repo name

- sjb-PWA-Text-Editor

###### GitHub enviroment

- https://github.com/simmmmo/sjb-PWA-Text-Editor
- git@github.com:simmmmo/sjb-PWA-Text-Editor.git

###### Heroku Environment

- https://sjb-pwa-texteditor.herokuapp.com/
