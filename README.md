# React Hooks and Firebase Demo - Live Grocery List

The Live Grocery List app is a demonstration of using React Hooks to manage app state that is backed by a Firebase firestore backend. This app demonstrates using building in React hooks as well as custom hooks.

It is a fork of the project from this [excellent blog](https://blog.logrocket.com/react-hooks-with-firebase-firestore/) but uses Recoil for state managment instead of prop passing.

## Setup

This application uses Firebase services. Configuration required to connect to Firebase is defined in the [.env](.env) file (or .env.local) in the root of this repository.

Before building or running the app, you must add your Firebase project configuration. Configuration can be obtained from _Project Settings_ in your Firebase project at [https://console.firebase.google.com](https://console.firebase.google.com).

## Available Scripts

In the project directory, you can run:

`npm start` to run the app in development mode
`npm test` to launch the test runner in interactive watch mode
`npm run build` to bundle the app for production
`npm run eject` to eject React Scripts dependency
