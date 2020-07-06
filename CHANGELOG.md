# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html):

- MAJOR version when you make incompatible API changes,
- MINOR version when you add functionality in a backwards compatible manner, and
- PATCH version when you make backwards compatible bug fixes.

## [Unreleased]

### Added

### Changed

### Removed

### Fixed

## [0.0.1]

### Added
- Added security definitions section in swagger specification
- Added contact in info object of swagger specification
- Added tag descriptions in swagger specification
    
### Changed
- PATCH verb in swagger specification replaced with PUT verb and refers to a specific resource
- PUT response section in swagger specification updated to include 200 and 201 to indicate update or creation
- POST response for inventory-item in swagger specification changed to only the newly created resource
- DELETE verb added for Removal of inventory item from collection
- Resource name 'inventory' in swagger specification changed to 'inventory-items' when referring to collection

### Removed
- Removed support for insecure http protocol in swagger specification

### Fixed
- Corrected unused 'null' and indentation mistake in swagger specification

## [0.0.0] - 2020-07-06
### Added
- Original specification of the API defined by Vandelay Industries tech team.

### Changed

### Removed

### Fixed
