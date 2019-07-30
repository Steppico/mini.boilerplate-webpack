# Boilerplate with Webpack
### This was created during my time as a [Code Chrysalis](https://codechrysalis.io) Student

## Table of Contents

1.  [Introduction](#introduction)
1.  [Objectives](#objectives)
1.  [Basic Requirements](#basic-requirements)
1.  [Resources](#resources)

## Introduction

Create an app from scratch using the `create-react-app` boilerplate tool, and run the app in development and production.

## Objectives

In this task you will:

* Create an app using a boilerplate tool
* Run that app with hot-reloading and a development server
* Connect the production build to a simple server using Express
* Eject the app and explore the Webpack config files

## Basic Requirements

### 1. Set up your boilerplate

* [ ] Use the [create-react-app](https://github.com/facebook/create-react-app) scaffolding tool to create a new boilerplate app in this folder.

### 2. Run your app in development

* [ ] Run your development server with `yarn start`. Test that hot-reloading is working by changing some of the text in `src/App.js` (for example, "Learn React") and then saving the changes. Your app should re-compile instantly and your changes should appear in the browser. 
  - Something to consider: if the app you created is in its own folder, you will need to run scripts from that subdirectory.

### 3. Create your production build

* [ ] Now, create a production build of your app using `yarn build`. This should create an output folder of your transpiled and minified code. It is static, so it doesn't change if your code changes– you need to run the script again.
  - What is the name of the output folder?

### 4. Create a server that points to your production build.

* [ ] Your production build doesn't come with a server– so you'll need to create it.
  - Create a file named `server.js` at the root level of your React app.
  - Create a basic express server and point it to your static build file using [express.static](https://expressjs.com/en/starter/static-files.html)
* [ ] Modify the scripts in your package.json with the following names so that they better reflect the differences between dev, build, and prod:
  - `yarn dev` should run your development server (this is what `yarn start` was previously doing)
  - `yarn build` should create your production build
  - `yarn start` should run the server you just created
  - `yarn prod` should run `yarn build && yarn start` (confirm that it is working by viewing your app in your browser!)

### 5. Explore the Webpack Config

`create-react-app` manages Webpack for you, but when your app gets bigger, you'll want to be able to control these configurations yourself. So let's see what's going on under the hood.

* [ ] Run `yarn eject` and expose all the configurations that were being auto-magically controlled for you.
* [ ] Look in the `config` directory. Try and understand why these files are needed.

### 6. Answer the questions for this activity.

* [ ] The questions are located in the file `questions.md`. Use specific examples whenever possible!
* [ ] When you are finished, make a pull request. IMPORTANT: If you have navigated to a subdirectory in your terminal, don't forget to return to the root level before committing your changes to Github. 

## Resources

* [Create React App - Github](https://github.com/facebook/create-react-app)
* [WebpackJS Concepts](https://webpack.js.org/concepts)
