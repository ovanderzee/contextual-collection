# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]


## [1.2.0] - 2020-11-27

Structural update
### Changed
* Confine prototype to methods
* Update readme with trinity of features


## [1.1.2] - 2020-11-09

Refined functionality
### Changed
* sort method uses well structured library function


## [1.1.1] - 2020-11-04

Refined functionality
### Changed
* sort method uses structured way to find a string


## [1.1.0] - 2020-11-03

More functionality
### Added
* yielding method: sort - sorts number numeric, strings alphabetic


## [1.0.0] - 2020-09-30

Methods for less coding
### Added
* maintenance methods: cross, drop, hold
* all maintenance methods return the current data as array.


## [0.6.0] - 2020-09-29

Towards production
### Changed
* standardised CHANGELOG to meet [Keep a Changelog](https://keepachangelog.com/nl/1.0.0/)
* sanitise core methods delete, get, has and set


## [0.5.0] - 2020-09-25

Enhanced documentation and extended API to match development needs.
### Added
* clearified add function in README
* output method: where
### Changed
* split methods file in files maintenance and yielding functions
* fix typos in js-docs


## [0.3.0] - 2020-09-18

Maturing project and extending API to match development needs.
### Added
* travis and coveralls badges
* coding examples in README
* CHANGELOG
* maintenance method: clear
### Changed
* refactored combination, intersection and their helper functions
* punctuation in js-docs


## [0.2.0] - 2020-09-02

A definate name with an extended API.
### Added
* maintenance method: toggle
* output methods: combination, intersection
* unit tests
* automated API documentation
### Changed
* changed name to SnapCollect
* renamed property 'keyProperty' as 'identifier'
* moved API and helper functions to dedicated files


## [0.1.0] - 2020-08-28

First release named ContextualCollection,
a simple working ready-to-use function.
Set-up copied from my-lib.
### Added
* maintenance method: add
* core methods: delete, get, has, set
* properties: keyProperty, length
* output methods: entries, keys, values
* demo.html with proofing


## [Ideas]

* Specify a criterion for acceptance || rejection when initialising,
  the criterion should also play a role in the processing.
* Support for Set-objects in combination/intersection
* subtraction, subtractionFrom
