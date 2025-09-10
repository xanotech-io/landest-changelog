# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.0.1] - 2025-06-27 - version 1.0.1

### Changed

- Refactored user wallet transaction logic.
- Improved error handling for user wallet operations.
- Updated wallet balance type from `decimal` to `int` for better precision since values are saved in the lowest denomination (kobo).

## [0.0.0] - 2025-05-27

### Added

- Initial release of the project.
- User wallet creation and management.
- User wallet transaction history.
- User wallet balance retrieval.
