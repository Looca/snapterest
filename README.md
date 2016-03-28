# Snapterest - ReactJS app

This app is based on tutorial from React.js Essentials book by Artemij Fedosejev: http://reactessentials.com/. This app utilizes [Twitters API](https://apps.twitter.com) using [Snapkit Engine](https://github.com/Snapkite/snapkite-engine) and takes advantage of data flow architecture using [Flux](https://facebook.github.io/flux/)

## Setup
1. Configure Snapkit engine as to use filters and Twitter API
2. Run Snapkit engine with: `npm start` command
3. navigate to './snapterest' directory and run `npm install` to install all node modules
4. Build app using `gulp` command
5. open './build/index.html' in the browser to see the results


## Test

Tests app using Jest Unit testing  [Jest](https://facebook.github.io/jest/ "Jest Hompage")
To test app run `npm test`  command.
Tested files directories are:
* './components/`__test__`'
* './utils/`__test__`'

## Misc.
* React.js Essentials [GitHub repo](https://github.com/fedosejev/react-essentials)
* Book [Updates](https://github.com/fedosejev/react-essentials/blob/master/updates.md#chapter-8-page-6)
* When using Node >= 4 make sure to update Jest CLi to version >= 0.9 Otherwise runing `npm test` may return errors when testing Button.js and Header.js
