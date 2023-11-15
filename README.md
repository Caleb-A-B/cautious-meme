# progressive-web-application-text-editor
## Table of Contents
1. [Description](#description)
2. [Technology](#technology)
3. [Installation](#installation)
5. [License](#license)

## Description
This is a progressive web application that can function in a browser operating both online and offline. Additionally, the app can be used in a freestanding context and still operate correctly (by use of an integrated service worker and Cache APIs). The goal was to showcase a platform for users to be able to take notes or write code snippets regardless of having an active internet connection.

## Technology
This application uses Express, IndexedDB, Webpack & WebpackPwaManifest Plugins, Concurrently, Babel, Babel extensions, and Heroku to live host the finished product. 

## Installation
Run 'npm i' within the console, located at the root level of the directory. This will pull in the necessary node modules/packages from the root, client, and server level package.json files. 

Once necessary dependencies are installed, "npm run start:dev" (or 'nodemon server.js" if you have nodemon installed) in the console to concurrently build out and start the client and server simultaneously.

Optionally, this application is deployed live via Heroku, and can be accessed via the link above.

## License
This application is licensed with the MIT License.