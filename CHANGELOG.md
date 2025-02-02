# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2021-05-13

### Added

- Add AllowRoot option to prevent backward incompatible. (#13)

### Changed

- Upgrade to v0.20.0 of `go.opentelemetry.io/otel`. (#8)
- otelsql will not create root spans in absence of existing spans by default. (#13)

## [0.2.1] - 2021-03-28

### Fixed

- otelsql does not set the status of span to Error while recording error. (#5)

## [0.2.0] - 2021-03-24

### Changed

- Upgrade to v0.19.0 of `go.opentelemetry.io/otel`. (#3)

## [0.1.0] - 2021-03-23

This is the first release of otelsql.
It contains instrumentation for trace and depends on OTel `v0.18.0`.

### Added

- Instrumentation for trace.
- CI files.
- Example code for a basic usage.
- Apache-2.0 license.

[Unreleased]: https://github.com/XSAM/otelsql/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/XSAM/otelsql/releases/tag/v0.3.0
[0.2.1]: https://github.com/XSAM/otelsql/releases/tag/v0.2.1
[0.2.0]: https://github.com/XSAM/otelsql/releases/tag/v0.2.0
[0.1.0]: https://github.com/XSAM/otelsql/releases/tag/v0.1.0
