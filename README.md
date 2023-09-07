
## Description

Created by using [Create React App](https://github.com/facebook/create-react-app)  with following libraries including:

  - React v17.0.2
  - Type Checker - TypeScript
  - API client - Relay
  - MUI
  - State management - Redux Thunk & Toolkit
  - Cypress
  - Format & Lint - ESLint & Prettier

Custom Templates, format, and ESlint configurations.

## Setup Environments
  - Node 16.2.0
  - Yarn 1.22.17

  ```
  npm install
  ```

  or
  ```
  yarn install
  ```

## Run Scripts

Inside the project directory run:

- `yarn start` - runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
- `yarn test` - launches the test runner in the interactive watch mode.
- `yarn build` - builds the app for production to the `build` folder.
- `yarn build:serve` - run a local static build using the production build using serve library. Install `yarn install -g serve`.
- `yarn eject` - exposes content of `react-script` package
- `yarn fix` - fix lint errors.
- `yarn relay` - generate graphql queries.
- `yarn cypress:open test` - run cypress test

## State Management

The code is set for [Redux Toolkit](https://medium.com/react-courses/instant-learn-react-redux-toolkit-with-a-simple-minimalistic-example-3c63c296ed65) you pick.

## API Client

[Relay](https://relay.dev/) keeps management of data-fetching easy, whether your app has tens, hundreds, or thousands of components.

## Eslint configurations

Lint is set according to Airbnb style guide — as part of their style guide.

