# text_editor

## Table of Contents

* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Technologies](#technologies)
* [Repo](#code-repository)
* [URL](#live-application)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)

## Description

This app is a text editor that meets PWA criteria. This single page application can run in the browser and offline. Additionally, it will features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application  also functions offline.

### User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use.
```

### Acceptance Criteria

```
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

### Technologies

To create this application, I used:
- IndexedDB to save content
- Webpack to bundle front-end code
- Workbox to create a service worker that caches static assets
- Heroku to deploy

### Screenshot of Application

![Screenshot of Text_Editor](./client/dist/assets/JateTextEditor.png)

### Code Repository

The repository where the code is saved is on Github. To access it, click [This Repo](https://github.com/RedactdName/text_editor.git).

### Live Application

This application is deployed on Heroku.  Click [here](https://vast-shelf-09420-acf42c4fdeb8.herokuapp.com/)

## Installation

To install necessary dependencies, run the following command:

```
npm i
```

## Usage

To use the application from the command line (after installing dependencies):
1. Open the root directory of the repository in your terminal or bash.
2. Bundle the front-end code by entering ```npm run build``` in the command line.
3. Start the server by entering ```npm run start``` in the command line.
4. Go to the port on your local host.
5. Click the "Install" button.

Alternatively, to use the live application, click [here](https://vast-shelf-09420-acf42c4fdeb8.herokuapp.com/).

## Credits

- This is the [starter code](https://github.com/coding-boot-camp/cautious-meme) that was used.