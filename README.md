### Demo
You can check [Live Demo here](https://tik-toe-toy-online-d475f.firebaseapp.com).

All the commands to build, deploy push and commit are in `package.json`.

# ReactJS + Firebase

## React
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn define`

Disable all eslint warnings by adding esling-disable command at the beging and in the end of each JS file.

### `yarn deploy`

Deploying `build` folder to the server.

### `yarn commit`

Creating a commit with name in format DD.MM.YYYY🌿HH:mm and pushing it.

### `yarn produce`

Compilation of `define` + `build` + `deploy` + `commit`.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

## Firebase
All firebase configs are in `src/constants/config.js`.

To initialize firebase - you need to have a `firebase-tools` (https://firebase.google.com/docs/cli#macos).
We are using both firebase and surge.sh hosting.
