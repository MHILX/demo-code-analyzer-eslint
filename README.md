# ESLint Demo with React App

## Getting Started with Create React App / Available Scripts

### Set npm registry for the current project
    npm config set registry https://registry.npmjs.org/

You have to run the above command if the default registry is set to https://npm.pkg.github.com, otherwise the CRA command will fail. Alternatively, you can set it for the current project by adding the following line to the `.npmrc` file in the root of the project.

### Create a react app
    npx create-react-app . --template typescript --registry=https://registry.npmjs.org

If you want to have assign a different app name, then remove the dot at the end of the command `npx create-react-app .` and add the app name.

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

---

## ESLint Setup

To learn ESLint, check out the [ESLint documentation](https://eslint.org/).

### Install ESLint
    npm install eslint eslint-plugin-react eslint-plugin-react-hooks --save-dev

### Initialize ESLint
    npx eslint --init

### Install eslint-plugin-react
    npm install eslint-plugin-react --save-dev
