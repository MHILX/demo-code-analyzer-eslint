# ESLint Demo with React App

### Set npm registry for the current project
    npm config set registry https://registry.npmjs.org/

You have to run the above command if the default registry is set to https://npm.pkg.github.com, otherwise the CRA command will fail. Alternatively, you can set it for the current project by adding the following line to the `.npmrc` file in the root of the project.

    registry=https://registry.npmjs.org/

### Create a react app
    npx create-react-app . --template typescript --registry=https://registry.npmjs.org

If you want to have assign a different app name, then remove the dot at the end of the command `npx create-react-app .` and add the app name.

### Install ESLint
    npm install eslint eslint-plugin-react eslint-plugin-react-hooks --save-dev

### Initialize ESLint
    npx eslint --init

### Install eslint-plugin-react
    npm install eslint-plugin-react --save-dev


