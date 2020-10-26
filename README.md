# Getting Started with Create React App

2c275a215e202d3860aa

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Application Features:

-Periodically (every 10 seconds) poll for new posts from this API https://hn.algolia.com/api/v1/search_by_date?tags=story&page=0 via a GET request.

-New posts fetched after 10 seconds will be added to old posts.

-Increase page count in each subsequent get request.

-Implement pagination when the list is scrolled.

-The pagination and periodic request both should work mutually exclusive i.e for each request page number will be increased. Request with the same page number should never be made.

-Display the title, URL, created_at, and author of each post in a table.

-Upon selecting a row in the table, the user is taken to a new page that displays the raw JSON.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
