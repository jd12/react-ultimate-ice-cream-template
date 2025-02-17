# Ultimate Ice Cream

This is the project build application for the Ultimate Courses React Basics course.

It was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Although you can use `npm` this project currently contains a `yarn.lock` file and therefore prefers [Yarn](https://yarnpkg.com/en/). Feel free to delete the lock file if you prefer `npm` and know how it works.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

This project contains no tests at this stage but the testing infrastructure remains in place for you.

### `npm build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### `npm start-server`

The project contains a [Node](https://nodejs.org/en/) [Express](https://expressjs.com/) server with a number of RESTfull endpoints that provides all the data the application requires.

The server must be started on port `5000` for the application to function. This can be achieved by running the `start-server` command.

### `npm format`

This code base is formatted with [Prettier](https://github.com/prettier/prettier). Running this command will format all code files inside the `src` directory with `Prettier`.
