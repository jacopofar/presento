# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] - 2023-03-15

### Changed

- Add a title on the column layout that is placed before columns
- Use fitted title styling automatically for Markdown `h2` elements
- Use reveal.js Markdown functionality, instead of generating it in Python
- Allow extra style to be added to single slides or the whole presentation
## [0.2.0] - 2023-03-14

### Changed

- Allow theming
- Add column layout helper on single slides
- Allow custom port for the server
### Fixed
- Use a foreground process for thye HTTP server after initialization, so it does not remain active in background
## [0.1.4] - 2023-03-14

### Changed

- Avoid `|` type union that breaks on Python 3.9

## [0.1.3] - 2023-03-14

### Changed

- Remove dependency on IPython, was not used in library code

## [0.1.2] - 2023-03-14

### Changed

- Require Python >= 3.9, not 3.10

## [0.1.1] - 2023-03-14

### Changed

- Added project URLs and changelog

## [0.1.0] - 2023-03-14

### Changed

- Published as a package to Pypi

