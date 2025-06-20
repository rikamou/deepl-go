# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.0] - 2023-11-24

This is a big refactoring release that contains breaking changes in both library
and command-line interfaces and restructures the project layout.

### Added

 - Retry with backoff logic in api calls

### Changed

 - Make translator http client an interface
 - Use JSON in library request bodies where possible and cli output

### Removed

 - `spf13/cobra` dependencies
 - Obsolete internal `Table` implementation

## [0.4.0] - 2023-02-20

### Added

 - `--source/--target` shorthand flags for `languages` command
 - `document` endpoint actions

### Changed

 - Change `TranslateOption` implementation from functional options to key-value pairs
 - Adjust command outputs to verbosity flag count

## [0.3.0] - 2023-02-17

### Added

- `version` command displaying the version and optionally commit of the cli
- `/glossary-language-pairs` and `/glossaries` endpoint actions

### Changed

- `verbose` flag can be passed multiple times for different verbosity levels

## [0.2.0] - 2023-02-13

### Added

- Add `/usage` and `/languages` endpoint actions

### Changed

- Align cases of help strings

## [0.1.0] - 2023-02-12

Initial version.

### Added

- Add text translation api and cli


[Unreleased]: https://github.com/rikamou/deepl-go/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/rikamou/deepl-go/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/rikamou/deepl-go/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/rikamou/deepl-go/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/rikamou/deepl-go/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/rikamou/deepl-go/releases/tag/v0.1.0

