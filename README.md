# landest-changelog

This repository is dedicated to storing and managing changelogs for the various Landest applications and services. Each application or service has its own directory containing a `CHANGELOG.md` file that documents its release history, updates, and changes.

## Changelogs by Application

- [Account Service](./account-service/CHANGELOG.md)
- [API Gateway](./api-gateway/CHANGELOG.md)
- [Notification Service](./notification-service/CHANGELOG.md)
- [Property Service](./property-service/CHANGELOG.md)
- [Thirdparty Provider](./thirdparty-provider/CHANGELOG.md)
- [Transaction Service](./transaction-service/CHANGELOG.md)
- [User Service](./user-service/CHANGELOG.md)

## Example Changelog Entry

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