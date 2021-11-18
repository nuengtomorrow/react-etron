# React-Etron 
React integration electron for minimal project

## Creating an App
> npm
```sh
npx create-react-etron my-app
npm install
```
>yarn

```sh
yarn create react-etron my-app
yarn install
```

It will create a directory called my-app inside the current folder.
Inside that directory, it will generate the initial project structure and install the transitive dependencies:
```sh
my-app
├─ README.md
├─ package.json
├─ electron-builder.yml
├─ public
│  ├─ electron.js
│  ├─ index.html
│  └─ logo.png
└─ src
   ├─ App.js
   ├─ index.css
   └─ index.js
```

## Getting Started with React Etron

Available Scripts in the project directory, you can run:

### `react:start`
Runs react on browser in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `react:build`
Builds the react app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

### `electron:build`
main script for build all platform windows mac and linux from default electron configuration.

### `start`
Runs electron app in the development mode on window open.

### `build:all`
Build the electron app on windows mac and linux for production to the `dist` folder.

### `build:win`
Build the electron app on windows for production to the `dist` folder.

### `build:mac`
Build the electron app on macOs for production to the `dist` folder.

### `build:linux`
Build the electron app on linux for production to the `dist` folder.

## Configuration
> `Development`
> * you can change main configuration for your app, is run on electron in `electron.js`

> `Production`
> * you can change configuration icon, target package type, function for application and more in `electron-builder.yml`

## Learn More
> Development
> - [electron.js](https://www.electronjs.org/docs/latest)

> Production
> - [electron-builder](https://www.electron.build/)
