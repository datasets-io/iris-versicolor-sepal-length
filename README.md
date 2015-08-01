Iris Versicolor Sepal Length
===
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][codecov-image]][codecov-url] [![Dependencies][dependencies-image]][dependencies-url]

> Edgar Anderson's [data](https://en.wikipedia.org/wiki/Iris_flower_data_set) for *Iris versicolor* sepal length.


## Installation

``` bash
$ npm install datasets-iris-versicolor-sepal-length
```

For use in the browser, use [browserify](https://github.com/substack/node-browserify).


## Usage

``` javascript
var data = require( 'datasets-iris-versicolor-sepal-length' );
```

#### data

Edgar Anderson's [data](https://en.wikipedia.org/wiki/Iris_flower_data_set) for *Iris versicolor* sepal length.

``` javascript
console.log( data );
// returns [ 7, 6.4, 6.9, ... ]
```

All values are in `centimeters`.


## Examples

``` javascript
var mean = require( 'compute-mean' ),
	variance = require( 'compute-variance' ),
	data = require( 'datasets-iris-versicolor-sepal-length' );

// Calculate the sample mean:
console.log( mean( data ) );

// Calculate the sample variance:
console.log( variance( data ) );
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


## References

*	Anderson, Edgar (1935). "The irises of the Gaspe Peninsula," *Bulletin of the American Iris Society*, __59__, 2–5.
*	Fisher, Ronald A. (1936). "The use of multiple measurements in taxonomic problems." *Annals of Eugenics*, __7__, Part II, 179–188.


## See Also

*	[iris](https://github.com/datasets-io/iris)
*	[iris-versicolor](https://github.com/datasets-io/iris-versicolor)
*	[iris-versicolor-sepal](https://github.com/datasets-io/iris-versicolor-sepal)


## Tests

### Unit

Unit tests use the [Mocha](http://mochajs.org/) test framework with [Chai](http://chaijs.com) assertions. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul](https://github.com/gotwarlost/istanbul) as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015. The [Compute.io](https://github.com/compute-io) Authors.


[npm-image]: http://img.shields.io/npm/v/datasets-iris-versicolor-sepal-length.svg
[npm-url]: https://npmjs.org/package/datasets-iris-versicolor-sepal-length

[travis-image]: http://img.shields.io/travis/datasets-io/iris-versicolor-sepal-length/master.svg
[travis-url]: https://travis-ci.org/datasets-io/iris-versicolor-sepal-length

[codecov-image]: https://img.shields.io/codecov/c/github/datasets-io/iris-versicolor-sepal-length/master.svg
[codecov-url]: https://codecov.io/github/datasets-io/iris-versicolor-sepal-length?branch=master

[dependencies-image]: http://img.shields.io/david/datasets-io/iris-versicolor-sepal-length.svg
[dependencies-url]: https://david-dm.org/datasets-io/iris-versicolor-sepal-length

[dev-dependencies-image]: http://img.shields.io/david/dev/datasets-io/iris-versicolor-sepal-length.svg
[dev-dependencies-url]: https://david-dm.org/dev/datasets-io/iris-versicolor-sepal-length

[github-issues-image]: http://img.shields.io/github/issues/datasets-io/iris-versicolor-sepal-length.svg
[github-issues-url]: https://github.com/datasets-io/iris-versicolor-sepal-length/issues
