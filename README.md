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
