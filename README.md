 [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-url]][daviddm-image]
 
# Conditional estimation of Rasch model

Both the R script "iterativeML" and the estimation.JS estimate the parameters the Rasch model/Bradley-Terry_Luce model with a
conditional maximum likelihood procedure. This procedure is an iterative procedure using Newton's method of optimization.
This procedure was initially developed by Rasch (1960) and implemented by Pollitt (2012) and [NoMoreMarking ltd.](https://github.com/NoMoreMarking/cj) among others.

Both Scripts were based on the code of [NoMoreMarking ltd.](https://github.com/NoMoreMarking/cj).

The estimation.js is tested in the estimation.test.js in conjunction with the "data for testing.R" file. The estimation
is working good.

The estimateCJ and CML functions are the translation of the [NoMoreMarking ltd.](https://github.com/NoMoreMarking/cj)algorithms for use in the [D-PAC](https://github.com/d-pac) tool. And the
ConvertData function is to convert the data that the [D-PAC](https://github.com/d-pac) tool provides to data the estimateCJ and CML functions can
handle.

raschStats.js contains functions to calculate the Rasch probability and the Fischer Information.

[npm-url]: https://npmjs.org/package/estimating-rasch-model
[npm-image]: https://badge.fury.io/js/estimating-rasch-model.svg
[travis-url]: https://travis-ci.org/d-pac/estimating-rasch-model
[travis-image]: https://travis-ci.org/d-pac/estimating-rasch-model.svg?branch=master
[daviddm-url]: https://david-dm.org/d-pac/estimating-rasch-model.svg?theme=shields.io
[daviddm-image]: https://david-dm.org/d-pac/estimating-rasch-model
