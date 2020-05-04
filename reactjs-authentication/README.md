This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Overview

This provides boilerplate code for building a valid login/sign-in page using Reactjs framework. The project utilizes [material ui](https://material-ui.com/) for layout, show cases use of React functional components [login.layout.js](/src/login/login.layout.js) and React class components [login.component.js](/src/login/login.component.js).

The project supports applying themes to a site using (MuiThemeProvider)(/src/App.js).

[Authentication service](/src/auth/auth.service.js) should be updated to validate the login against any token based auth API. The service uses local storage for persisting the login info that is used for validating whether user is authenticated or not. 

# Steps to run the project
1. Download the code
1. Run `yarn` to install necessary packages and dependencies
1. Run `yarn start`
