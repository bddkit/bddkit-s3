# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.1](https://github.com/bddkit/bddkit-s3/compare/v0.3.0...v0.3.1) - 2026-10-30

### Other

- add CLAUDE.md for coding agents

## [0.3.0](https://github.com/bddkit/bddkit-s3/compare/v0.2.1...v0.3.0) - 2026-10-30

### Added

- [**breaking**] plugin ABI 3 (bddkit/bddkit#173)

## [0.2.1](https://github.com/bddkit/bddkit-s3/compare/v0.2.0...v0.2.1) - 2026-10-16

### Added

- publish bddkit-plugin.json with every release (bddkit/bddkit-s3#12)

## [0.2.0](https://github.com/bddkit/bddkit-s3/compare/v0.1.0...v0.2.0) - 2026-10-13

### Added

- [**breaking**] speak plugin ABI 2 (bddkit/bddkit#90)
- [**breaking**] describe the s3 config keys, and probe one live

### Other

- run e2e against Garage, MinIO images are no longer published ([#9](https://github.com/bddkit/bddkit-s3/pull/9))
- execute the probe's live branches, and document the contract
- drive the config contract through a real host
- run the end-to-end suite against a published bddkit
- streamline README
