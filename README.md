# APPII React
This project started from [base-react-app](https://github.com/appliedblockchain/base-react-app)

React app based on create-react-app but adding enzyme, redux, react-router

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app)

## Getting started

```
npm i
chmod 777 node_modules/pre-commit/hook
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests) for more information.

### `npm run build`

You shouldn't need to run this, as the app is built and deployed on the CI.

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#deployment) for more information.

### Create an account on Test environment

* Go to https://test-jdc9nn.appii.io/register
* You will receive an email to confirm your email
* Check that you can login: https://test-jdc9nn.appii.io/login
* Using `REACT_APP_API_ENV=test npm start` you can hit `test` B/E API locally, so you can login with the test account you just created

NOTE: You can follow the same steps for local or staging

For local you will need to install B/E code and run the server => https://github.com/appliedblockchain/appii-js

### Choosing API Environment

Currently, the default environment is `test`

Other environments available are `local`, `test`, `staging`, `production`

You can build for environments by passing the `REACT_APP_API_ENV` ENV var. Example;

`REACT_APP_API_ENV=local npm start`

*Developer note: If we use any more environment variables in the app, we should switch to using `.env` which this boilerplate already supports*
