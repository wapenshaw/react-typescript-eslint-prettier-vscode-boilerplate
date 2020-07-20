This is a Create React App ejected and version bumped to @latest as on 21-Jul, CRA was still on ESLint 6.x so (っ °Д °;)っ

This is geared for VSCode and has all project/extension specific settings included, such as

1. TSConfig
2. ESLint with TS plugins and the necessary `.eslintrc` config file
3. Prettier Plugins and their corresponding `.prettierrc` file
4. An `.env` file which tells the script to not open the link in default browser ~(>_<。)
5. Launch configuration for VSCode, Install Chrome debugger extension and hit `F5` to start debugging immediately. If you have the [Browser Preview Extension](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) you can use that with F5 as well.
6. Extension specific settings already added in `settings.json`.


## 4 Simple Steps

1. Git clone this repo
`git clone https://github.com/wapenshaw/react-typescript-eslint-prettier-vscode.git`

2. `code .` from inside the project folder or `Open Folder` in VSCode

3. `npm install` or `yarn install` <- preffered

4. `npm start` or `yarn start`



## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
