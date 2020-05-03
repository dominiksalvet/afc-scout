# Changelog

All notable changes to afc-scout will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and afc-scout adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

The changes not yet present in any release are listed in this section.

### Changed

* Interesting address ranges are printed instead of dumping all when run without arguments.

### Removed

* The check for existing commands has been removed as those are mandatory commands.

## 1.1.1 (2020-02-23)

### Fixed

* Check whether start address is less or equal to end address.

## 1.1.0 (2020-02-23)

### Added

* The support for local GitPack installation has been added.

## 1.0.0 (2020-02-23)

### Added

* Added support for reading interesting ACPI address range.
* Added support for reading ACPI values on custom address range.
