# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

## 0.1.20 - 2019-01-28

### Fixed
- Check status and version to find peers
- Clone peer list as to not overwrite default network peers

## 0.1.19 - 2019-01-25

### Changed
- Added transaction fees v2 endpoint

## 0.1.18 - 2019-01-22

### Changed
- Allow https peer option when finding peers

## 0.1.17 - 2019-01-16

### Changed
- Use standard API-Version header

## 0.1.16 - 2018-12-04

### Fixed
- Update mainnet peer addresses to match Core

## 0.1.15 - 2018-12-04

### Fixed
- Use API port for mainnet peers

## 0.1.14 - 2018-11-27

### Changed
- Update mainnet peer list

## 0.1.13 - 2018-11-26

### Changed
- Update mainnet peer list

## 0.1.12 - 2018-11-23

### Changed
- Get peer list from 2 peers

## 0.1.11 - 2018-11-23

### Changed
- Always send the `Content-Type` header

## 0.1.10 - 2018-10-24

### Fixed
- Use the configured `core-api` port instead of the `core-p2p` port, which would fail (https://github.com/ArkEcosystem/core/pull/1138)
- Wrong loader methods (https://github.com/ArkEcosystem/core/pull/1194)

## 0.1.9 - 2018-10-13

### Fixed
- Handle v2 endpoints when finding peers (https://github.com/ArkEcosystem/core/pull/1103)

## 0.1.8 - 2018-10-12

### Changed
- Use 5 second timeout for finding peers (https://github.com/ArkEcosystem/core/pull/1103)

### Fixed
- Get peer response data correctly (https://github.com/ArkEcosystem/core/pull/1103)

## 0.1.7 - 2018-10-12

### Fixed
- Add query parameters to the v2 endpoints.(https://github.com/ArkEcosystem/core/pull/1103)

## 0.1.6 - 2018-10-09

### Fixed
- Use the definitive `accept` header instead of the previous one (https://github.com/ArkEcosystem/core/pull/1082)

## 0.1.5 - 2018-10-05

### Fixed
- Use the `accept` header instead of api-version to avoid CORS problems (https://github.com/ArkEcosystem/core/pull/1012)

## 0.1.4 - 2018-09-20

### Fixed
- Fix API client HTTP params (query string) (https://github.com/ArkEcosystem/core/pull/1015)

## 0.1.3

...

## 0.1.1 - 2018-06-14

### Added
- initial release
