# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [0.0.1]

### Added

- App-as-Code service definition for ntfy using the upstream `binwiederhier/ntfy` image.
- Web interface and API on port 80, published externally on port 25125.
- Persistent volumes for the message cache and configuration directory.
- Container health check against `/v1/health`.
- README with configuration reference and project icon.
