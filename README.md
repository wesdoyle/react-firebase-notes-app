# react-firebase-notes-app
## Summary
A simple CRUD application to explore React and Firebase interaction. Implements a simple flexbox layout, and provides the ability for a user to add and remove notes from a Firebase database. I created a video tutorial for building the initial version of this app here: [Link to YouTube video](https://youtu.be/-RtJroTMDf4).

## Setup
You'll need to get your connection strings from Firebase. Place a file called `config.js` in `src/Config/` that contains your Firebase config as a simple javascript object, exported as `DB_CONFIG`. For example,

```
export const DB_CONFIG ={
  apiKey: your_api_key,
  authDomain: your_auth_domain,
  // etc..
}
```

## Starting the app
`npm start`

## Sample Screenshot

![example screenshot](https://github.com/wesdoyle/react-firebase-notes-app/blob/master/src/app.JPG)



This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
