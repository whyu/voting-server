# Redux voting server
* ES6 transpiled to ES5 thru Babel
* Test Framework: Mocha + Chai (assertion / expectation)
 
To Run Tests:
**./node_modules/mocha/bin/mocha --compilers

To transpile:
** js:babel-core/register --recursive


## Add to package.json

    "scripts": {
      "test": "mocha --compilers js:babel-core/register --recursive"
    }

    "babel": {
      "presets": ["es2015"]
    }

    npm run test

## To Watch Code:

    "test:watch": "npm run test -- --watch"




