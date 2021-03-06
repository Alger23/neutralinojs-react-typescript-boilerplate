---
Neutralinojs binaries: v3.0.0
Neutralinojs client: v2.0.0
neu CLI: v7.0.0

react: v17.0.2
react-scripts: v4.0.3
typescript: v4.1.2
---

Neutralinojs + React + Typescript



```
npx degit alger23/neutralinojs-react-typescript-boilerplate my-app
cd my-app
neu update
yarn install
# first build for create ./resources folder and files 
yarn react-build
yarn start
```


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Run the Neutralinojs app in development mode. But React app with build. If you changes react app, you will need to stop and `yarn start` again.

### `yarn build`

Build the neu app into `./dist` folder.

### `yarn react-start`

Runs the react app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn react-test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn react-build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn react-eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

# Neutralinojs

## neutralinojs-minimal
The simplest template for a Neutralinojs app. It's possible to use your favorite frontend framework using the following steps.

- Create a new project using your favorite frontend framework. (Eg: `ng new --directory .`)
- Make the frontend framework's build path and Neutralino config's `url`, `resourcesPath` the same.
- Build with the correct base href.

## Icon credits

- `trayIcon.png` - Made by [Freepik](https://www.freepik.com) and downloaded from [Flaticon](https://www.flaticon.com)
