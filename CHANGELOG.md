# Changelog

All notable changes to Workstation Sentinel will be documented in this file.

The format is based on semantic versioning.

---

## [v0.2.1-beta] - 2026-03-11

### Improved
- Standardized memory usage column naming in generated CSV reports
- Minor internal code cleanup for readability

### Changed
- Updated CSV header naming for improved report clarity

---

## [v0.2.0-beta] - 2026-03-10

### Added
- CSV report generation
- Automatic filename generation using hostname and date
- Automatic report folder creation
- Structured data handling for system metrics

### Changed
- Refactored script to store collected metrics before generating output
- Improved disk data handling and formatting

### Fixed
- Prevented errors when handling systems with fewer drives than expected
- Ensured report directory exists before writing output files

---

## [v0.1.0] - Initial Release - 2026-03-10

### Added
- Platform information collection
- CPU utilization monitoring
- Memory statistics reporting
- Disk usage detection and reporting
- Console-based workstation health output