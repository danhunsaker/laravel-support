# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.7] - 2015-12-07
### Fixed
- Fix method calling from $this->guest() to $this->createGuest()

## [1.0.6] - 2015-12-06
### Fixed
- Add missing use statement.

## [1.0.5] - 2015-12-06
### Changed
- Extracted user model detection code into seperate re-usable helper
- Updated README
### Added
- Create .gitignore and .gitattributes files.

## [1.0.4] - 2015-10-22
### Fixed
- Fix config value retrieval for layout.

## [1.0.3] - 2015-09-30
### Fixed
- Fix Controller.php

## [1.0.2] - 2015-09-30
### Fixed
- Fixed missing ; after controller namespace.

## [1.0.1] - 2015-09-30
### Fixed
- Fixed ServiceProvider including non-existant routes file.

## [1.0.0] - 2015-09-30
### Added
- Added master layout which packages can extend (Includes jQuery/Bootstrap).
- Ability to configure sitename which can be used in depending packages.
- Ability to configure layout choice in one central package (makes site using multiple packages consistent).


[Unreleased]: https://github.com/taskforcedev/laravel-support/compare/v1.0.7...HEAD
[1.0.7]: https://github.com/taskforcedev/laravel-support/compare/v1.0.6...v1.0.7
[1.0.6]: https://github.com/taskforcedev/laravel-support/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/taskforcedev/laravel-support/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/taskforcedev/laravel-support/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/taskforcedev/laravel-support/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/taskforcedev/laravel-support/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/taskforcedev/laravel-support/compare/v1.0.0...v1.0.1
