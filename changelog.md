# Changelog

All notable changes to afc-scout will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and afc-scout adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

The changes not yet present in any release are listed in this section.

## 2.1.0 (2021-02-11)

### Changed

* Adapt to new GitPack 1.0.0 installation format.
* The acpi_call module is installed automatically on systems with APT.
* The acpi_call module is loaded on system boots using a systemd service.

### Fixed

* Fixed `ignored null byte in input` warning occurring on some systems.

### Removed

* Removed the support for local GitPack installation as it is unnecessary.

## 2.0.1 (2020-10-02)

### Fixed

* ACPI call errors now include the whole error description.

## 2.0.0 (2020-05-03)

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
