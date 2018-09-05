# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [6.1.2] - 2018-09-05
### Fixed
- Fix missing folder in npm package


## [6.1.1] - 2018-06-20
### Fixed
- Fix MS Windows Compatibility

## [6.1.0] - 2018-06-18
### Changed
- Add range check for 'N' parameter by chrisveness

### Fixed
- Add bindings dependency by fanatid
- Bugfix for `params()` and `paramsSync()` argument ordering of `maxmem` and `maxmemfrac` to match documentation by shanewholloway
- Include order matters by zilti
- Fixed issue with mixed up variables by lincolnanders5
- Fix deprecated warnings when compiling
- Fix broken error messages - overhaul

## [6.0.6] - 2018-06-18
### Fixed
- Remove unnecessary files

## [6.0.5] - 2018-06-18
### Fixed
- Fix scrypt update
- Fix travis build

## [6.0.4] - 2018-06-17
### Changed
- Update nan to 2.10.0
- Update scrypt to 1.2.1
- Replaced new Buffer (deprecated) with Buffer.from

### Fixed
- Fix broken error messages

## [6.0.2] - 2016-04-17
### Fixed
- Microsoft compile issues

## [5.4.1] - 2015-10-12
### Fixed
- Corrected Hash API documentation in README

## [5.4.0] - 2015-10-09
### Fixed
- Check for empty buffer (see #97)

## [5.3.0] - 2015-10-08
### Added
- This changelog file

### Changed
- Renamed Readme.md to README.md
- Inserted link to changelog in README.md

## [5.2.0] - 2015-10-06
### Fixed
- Allow building on MS 2015

## [5.1.1] - 2015-09-21
### Fixed
- Remove hardcoded nan paths - issue 92

## [5.1.0] - 2015-09-21
### Changed
- Updated Readme documentation to include .....

## [5.0] - 2015-09-13
### Added
- Made module ES6 Promise compatible
- ...

### Fixed
- Fixes ...

### Changed
- C++ addon code rewritten using Nan 2.x
- API has changed:
- Every output is a buffer.
- Separated functions into async and sync versions.
- Api name swap: What was kdf in previous versions is now hash (and vice versa).
- Async functions will return a Promise if no callback function is present and Promises are available (else it will throw a SyntaxError).
- Using correct JavaScript Error object for all errors
- Updated Readme documentation to include .....
