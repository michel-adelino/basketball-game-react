## Motivation

A basketball-themed quiz game built with React and TypeScript, combining coding practice with sports. The project is structured for steady iteration and learning.

## Disclaimer

This is a hobby project built for fun and learning. It may use a mix of styling approaches (inline styles, styled components, and CSS) and other choices that prioritize experimentation over consistency.

## Tracked user data (Mixpanel)

The project can use Mixpanel to track user actions. Below is an example of the dashboard.

![Image](readme-assets/mixpanel-dashboard.jpeg 'Basketball Game Dashboard in Mixpanel. It contains a conversion funnel and a pie chart.')

To enable tracking in your fork, set `REACT_APP_MIXPANEL_TOKEN` in your environment.

## API

The front end consumes the [nba-api-nodejs](https://github.com/michel-adelino/nba-api-nodejs) API.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload when you edit. Lint errors will appear in the console.

By default, the app uses the production API; no local API is required.

### `npm run start:local-api`

Same as `npm start`, but the app expects the API at `http://localhost:8080`.

To use this, clone, install, and run the [nba-api-nodejs](https://github.com/michel-adelino/nba-api-nodejs) project locally.

### `npm test`

Runs all unit tests with Jest.

### `npm run test:watch`

Runs the test runner in watch mode.  
See the [running tests](https://facebook.github.io/create-react-app/docs/running-tests) section in the Create React App docs.

### `npm run build`

Builds the app for production into the `build` folder.  
The bundle is minified and filenames include hashes.

See the [deployment](https://facebook.github.io/create-react-app/docs/deployment) section for deployment instructions.

### `npm run lint`

Reports lines that violate the project’s ESLint rules.

### `npm run lint:fix`

Runs ESLint and attempts to fix issues automatically.

## Learn more

- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React documentation](https://reactjs.org/)
