# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- `evaluate` scenario action (run a JavaScript expression in the page) and a `force` option on `click`.
- Standard community-health documentation (`CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`, `GOVERNANCE.md`, this changelog).

### Changed
- Demo capture skips the duplicate baseline load when the first demo step is a `goto`, runs setup after that navigation, and caps the baseline networkidle wait at 5s.

## [0.1.0]

### Added
- Initial documented release of Readme Showcase.
