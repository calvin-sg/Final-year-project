# Project title

A web app utilising backend rule-based decision-making in recommending location for food and beverage outlets with desired attributes for customers

## Demo Link

[![Site preview](/assets/Demo-FYP.gif)](https://calvin.sg)

Live demo of the application is deployed on Firebase, available at: [https://fyp-calvinloh-190428332.web.app/](https://fyp-calvinloh-190428332.web.app/).

Several video demonstrations of functioning web application and high-fidelity prototype is also attached to the submission of this project.

## Table of contents

* [About](#about)
* [Technologies and attributions](#technologies-and-attributions)
* [Terms and License](#terms-and-license)
* [Usage](#usage)
  * [Available Scripts](#available-scripts)
    * [npm start](#npm-start)
    * [npm test](#npm-test)
    * [npm run build](#npm-run-build)
    * [npm run eject](#npm-run-eject)

## About

- Problem statement identified as shortfalls in current methods among F&B management. 
- Project scope is in understanding customers motivations and location scouting for new outlets.
- Status quo involves the techniques used to gather customer desired attributes and optimal outlet location relies on mainly human intuition 
- and limited information technology tools, as identified in literature review and requirement gathering.

The proposed web application seeks to gather customer’s motivations, distill into these distinct criteria as input into this information system. 
Thereafter, this project aims to use rule-based decision-making based on specific business rules and customer inputs. 
The output of rule engine is displayed on the web application as a map with markers of target customers frequented locations and feature tiles for each desired attribute your restaurant is recommended to provide.

## Technologies and attributions

The project is built using the following technologies, attribution to the various projects and authors are as follows:
* [React](https://reactjs.org/)
* [Open-react-template](https://github.com/cruip/open-react-template)
* [Firebase](https://firebase.google.com/)
* [Unsplash](https://unsplash.com/)
* [json-rules-engine](https://github.com/CacheControl/json-rules-engine)
* [json-forms](https://jsonforms.io/)
* [mapbox-gl](https://www.mapbox.com/mapbox-gl-js/)
* [react-map-gl](https://github.com/alex3165/react-mapbox-gl)
* [emailjs](https://www.emailjs.com/)
* [mui](https://mui.com/)
* [Semantic UI](https://semantic-ui.com/)
* [sweetalert2](https://sweetalert2.github.io/)
* [Nucleo](https://nucleoapp.com/)

## Terms and License

- All rights reserved. 2022. Calvin.

## Usage

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm install`
To install the dependencies package.

#### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.