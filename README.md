# solysombra
A starting point for simple Javascript projects.

Dependencies in package.json are specified as * in order for solysombra
to run with the latest versions of packages available at the moment of
project generation. After running `npm install` you should run `npm update
--save` in order to fix the dependencies version to the ones you just
installed.


## Tests  
Mocha is used for testing, and the chai and sinon libraries are included.

## Lint  
You can run jscs linter using `npm run lint`, it will check the code under
`src/js` as ES6 using the [airbnb style guide](https://github.com/airbnb/javascript)
the configuration for [jscs](http://jscs.info/) is on `package.json` you can
change stuff there.

## Babel  
Write ES6 today and get it transpiled into ES5 that runs everywhere, to run babel do `npm run babel`, for now it only runs app.js through it and produces external source maps.  

## Other tasks  
- `npm run clean` will remove the files inside `dist/js/`
- `npm run build` runs the linter and copies app.js into `dist/js/`
- `npm run build:es5` runs lint and babel to trasnpile the code into ES5 and put it under `dist/js`
- `npm run watch` runs build after any change in app.js
- `npm run watch:es5` runs build:es5 after any change in app.js
