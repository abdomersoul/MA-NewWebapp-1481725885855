# Node.js Cloudant Starter Overview

The Node.js Cloudant Starter demonstrates how to use the Bluemix Cloudant NoSQL DB service. The app displays persisted files and lets the user upload new files or delete old files.

## Decomposition Instructions

* See app.js for how to obtain and use the Cloudant credentials as well as the file CRUD API
* See public/scripts/index.js and public/scripts/util.js for how the front-end calls the back-end API

## Running the app on Bluemix

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy)

The above button will deploy this application to your Bluemix by reading the manifest.yml file. This file describes the application to Bluemix, and also declares any necessary services (mysql).
