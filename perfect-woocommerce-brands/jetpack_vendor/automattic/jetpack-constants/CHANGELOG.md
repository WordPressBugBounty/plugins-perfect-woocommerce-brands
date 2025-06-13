# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.8] - 2025-04-28
### Changed
- Internal updates.

## [3.0.7] - 2025-04-14
### Changed
- Internal updates.

## [3.0.6] - 2025-03-31
### Changed
- Internal updates.

## [3.0.5] - 2025-03-21
### Changed
- Internal updates.

## [3.0.4] - 2025-03-12
### Changed
- Internal updates.

## [3.0.3] - 2025-03-05
### Changed
- Internal updates.

## [3.0.2] - 2025-02-24
### Changed
- Update dependencies.

## [3.0.1] - 2024-11-25
### Changed
- Updated package dependencies. [#40258]

## [3.0.0] - 2024-11-14
### Removed
- General: Update minimum PHP version to 7.2. [#40147]

## [2.0.5] - 2024-11-04
### Added
- Enable test coverage. [#39961]

## [2.0.4] - 2024-08-23
### Changed
- Updated package dependencies. [#39004]

## [2.0.3] - 2024-05-29
### Fixed
- Fix phpdoc type on `Constants::set_constant()` value parameter. [#37606]

## [2.0.2] - 2024-04-30
### Changed
- Internal updates.

## [2.0.1] - 2024-03-12
### Changed
- Internal updates.

## [2.0.0] - 2023-11-20
### Changed
- Updated required PHP version to >= 7.0. [#34192]

## [1.6.23] - 2023-08-23
### Changed
- Updated package dependencies. [#32605]

## [1.6.22] - 2023-04-10
### Added
- Add Jetpack Autoloader package suggestion. [#29988]

## [1.6.21] - 2023-02-20
### Changed
- Minor internal updates.

## [1.6.20] - 2022-12-02
### Changed
- Updated package dependencies. [#27688]

## [1.6.19] - 2022-11-22
### Changed
- Updated package dependencies. [#27043]

## [1.6.18] - 2022-07-26
### Changed
- Updated package dependencies. [#25158]

## [1.6.17] - 2022-06-21
### Changed
- Renaming master to trunk.

## [1.6.16] - 2022-04-26
### Changed
- Updated package dependencies.

## [1.6.15] - 2022-01-25
### Changed
- Updated package dependencies.

## [1.6.14] - 2022-01-04
### Changed
- Switch to pcov for code coverage.
- Updated package dependencies

## [1.6.13] - 2021-12-14
### Changed
- Updated package dependencies.

## [1.6.12] - 2021-11-22
### Changed
- Updated package dependencies

## [1.6.11] - 2021-11-02
### Changed
- Set `convertDeprecationsToExceptions` true in PHPUnit config.
- Update PHPUnit configs to include just what needs coverage rather than include everything then try to exclude stuff that doesn't.

## [1.6.10] - 2021-10-26
### Fixed
- Updated is_true docblock to be more accurate.

## [1.6.9] - 2021-10-13
### Changed
- Updated package dependencies.

## [1.6.8] - 2021-10-06
### Changed
- Updated package dependencies

## [1.6.7] - 2021-09-28
### Changed
- Updated package dependencies.

## [1.6.6] - 2021-08-30
### Changed
- Run composer update on test-php command instead of phpunit
- Tests: update PHPUnit polyfills dependency (yoast/phpunit-polyfills).
- Updated versions in annotations

## [1.6.5] - 2021-05-25
### Changed
- Updated package dependencies.

## [1.6.4] - 2021-04-08
### Changed
- Packaging and build changes, no change to the package itself.

## [1.6.3] - 2021-03-30
### Added
- Composer alias for dev-master, to improve dependencies

### Changed
- Update package dependencies.

### Fixed
- Use `composer update` rather than `install` in scripts, as composer.lock isn't checked in.

## [1.6.2] - 2021-02-05

- CI: Make tests more generic

## [1.6.1] - 2021-01-19

- Add mirror-repo information to all current composer packages
- Monorepo: Reorganize all projects

## [1.6.0] - 2020-12-14

- Update dependency brain/monkey to v2.6.0
- Pin dependencies
- Packages: Update for PHP 8 testing

## [1.5.1] - 2020-10-28

- Updated PHPCS: Packages and Debugger

## [1.5.0] - 2020-08-13

- CI: Try collect js coverage
- Docker: Add package testing shortcut

## [1.4.0] - 2020-07-01

- Package Unit tests: update test file names to make sure they runs in Travis

## [1.3.0] - 2020-06-22

- PHPCS: Clean up the packages

## [1.2.0] - 2020-04-15

- Use jp.com redirect in all links
- Connection: add a filter for setting Jetpack api constants

## [1.1.3] - 2019-11-08

- Packages: Use classmap instead of PSR-4

## [1.1.2] - 2019-10-28

- Packages: Add gitattributes files to all packages that need th…

## [1.1.1] - 2019-09-20

- Docs: Unify usage of @package phpdoc tags

## [1.1.0] - 2019-09-14

## 1.0.0 - 2019-07-09

- Packages: Finish the constants package

[3.0.8]: https://github.com/Automattic/jetpack-constants/compare/v3.0.7...v3.0.8
[3.0.7]: https://github.com/Automattic/jetpack-constants/compare/v3.0.6...v3.0.7
[3.0.6]: https://github.com/Automattic/jetpack-constants/compare/v3.0.5...v3.0.6
[3.0.5]: https://github.com/Automattic/jetpack-constants/compare/v3.0.4...v3.0.5
[3.0.4]: https://github.com/Automattic/jetpack-constants/compare/v3.0.3...v3.0.4
[3.0.3]: https://github.com/Automattic/jetpack-constants/compare/v3.0.2...v3.0.3
[3.0.2]: https://github.com/Automattic/jetpack-constants/compare/v3.0.1...v3.0.2
[3.0.1]: https://github.com/Automattic/jetpack-constants/compare/v3.0.0...v3.0.1
[3.0.0]: https://github.com/Automattic/jetpack-constants/compare/v2.0.5...v3.0.0
[2.0.5]: https://github.com/Automattic/jetpack-constants/compare/v2.0.4...v2.0.5
[2.0.4]: https://github.com/Automattic/jetpack-constants/compare/v2.0.3...v2.0.4
[2.0.3]: https://github.com/Automattic/jetpack-constants/compare/v2.0.2...v2.0.3
[2.0.2]: https://github.com/Automattic/jetpack-constants/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/Automattic/jetpack-constants/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/Automattic/jetpack-constants/compare/v1.6.23...v2.0.0
[1.6.23]: https://github.com/Automattic/jetpack-constants/compare/v1.6.22...v1.6.23
[1.6.22]: https://github.com/Automattic/jetpack-constants/compare/v1.6.21...v1.6.22
[1.6.21]: https://github.com/Automattic/jetpack-constants/compare/v1.6.20...v1.6.21
[1.6.20]: https://github.com/Automattic/jetpack-constants/compare/v1.6.19...v1.6.20
[1.6.19]: https://github.com/Automattic/jetpack-constants/compare/v1.6.18...v1.6.19
[1.6.18]: https://github.com/Automattic/jetpack-constants/compare/v1.6.17...v1.6.18
[1.6.17]: https://github.com/Automattic/jetpack-constants/compare/v1.6.16...v1.6.17
[1.6.16]: https://github.com/Automattic/jetpack-constants/compare/v1.6.15...v1.6.16
[1.6.15]: https://github.com/Automattic/jetpack-constants/compare/v1.6.14...v1.6.15
[1.6.14]: https://github.com/Automattic/jetpack-constants/compare/v1.6.13...v1.6.14
[1.6.13]: https://github.com/Automattic/jetpack-constants/compare/v1.6.12...v1.6.13
[1.6.12]: https://github.com/Automattic/jetpack-constants/compare/v1.6.11...v1.6.12
[1.6.11]: https://github.com/Automattic/jetpack-constants/compare/v1.6.10...v1.6.11
[1.6.10]: https://github.com/Automattic/jetpack-constants/compare/v1.6.9...v1.6.10
[1.6.9]: https://github.com/Automattic/jetpack-constants/compare/v1.6.8...v1.6.9
[1.6.8]: https://github.com/Automattic/jetpack-constants/compare/v1.6.7...v1.6.8
[1.6.7]: https://github.com/Automattic/jetpack-constants/compare/v1.6.6...v1.6.7
[1.6.6]: https://github.com/Automattic/jetpack-constants/compare/v1.6.5...v1.6.6
[1.6.5]: https://github.com/Automattic/jetpack-constants/compare/v1.6.4...v1.6.5
[1.6.4]: https://github.com/Automattic/jetpack-constants/compare/v1.6.3...v1.6.4
[1.6.3]: https://github.com/Automattic/jetpack-constants/compare/v1.6.2...v1.6.3
[1.6.2]: https://github.com/Automattic/jetpack-constants/compare/v1.6.1...v1.6.2
[1.6.1]: https://github.com/Automattic/jetpack-constants/compare/v1.6.0...v1.6.1
[1.6.0]: https://github.com/Automattic/jetpack-constants/compare/v1.5.1...v1.6.0
[1.5.1]: https://github.com/Automattic/jetpack-constants/compare/v1.5.0...v1.5.1
[1.5.0]: https://github.com/Automattic/jetpack-constants/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/Automattic/jetpack-constants/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/Automattic/jetpack-constants/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/Automattic/jetpack-constants/compare/v1.1.3...v1.2.0
[1.1.3]: https://github.com/Automattic/jetpack-constants/compare/v1.1.2...v1.1.3
[1.1.2]: https://github.com/Automattic/jetpack-constants/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/Automattic/jetpack-constants/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/Automattic/jetpack-constants/compare/v1.0.0...v1.1.0
