# 19 Progressive Web Applications (PWA)

## Main Task

A text editor and quick-notes taker that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Mock-Up

The following image demonstrates the application first view:

![image](https://github.com/MoisesPerez90/QuillCraft/assets/118077086/b26c242d-6256-4f7a-af65-83cdf4040c6f)

The following image shows the application's `manifest.json` file:

![image](https://github.com/MoisesPerez90/QuillCraft/assets/118077086/def36899-11c6-4a1a-865a-05cf5081fcff)

The following image shows the application's registered service worker:

![image](https://github.com/MoisesPerez90/QuillCraft/assets/118077086/ec13eb80-c97f-4206-9e79-9f344ffc23a4)

The following image shows the application's IndexedDB storage:

![image](https://github.com/MoisesPerez90/QuillCraft/assets/118077086/221e994c-b054-4228-8978-23db53c38d91)

## Installation 
To install this app, you may want to clone the repo. After that, you have to run the "npm install" command to install all the dependencies and node modules that are required. 

Finally, you must run the "npm run start" command to start the process. 

## Deployed APP URL
https://sheltered-depths-73551.herokuapp.com/
