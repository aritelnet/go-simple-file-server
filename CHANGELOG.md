# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-07-01

### Added

- Initial release of a simple file server written in Go
- Serves static files from the `htdocs/` directory on port `8080`
- Automatically creates the `htdocs/` directory if it does not exist
- Cross-platform support:
  - Linux (amd64, arm64)
  - Windows (amd64)
  - macOS (amd64, arm64)
- GitHub Actions-based CI/CD for cross-compilation and binary release
