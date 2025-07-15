# Changelog

All notable changes to this project will be documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

---

## [v0.0.0] - 2025-07-15

### Added
- Initial fork from MagpiEM v0.2.20.

### Changed
- Renamed project to **SocioMol**.
- Changed package folder from `MagpiEM` to `sociomol` to comply with PEP8.
- Renamed `static/` directory to `tmp/`.
- Updated `pyproject.toml`:
  - Project name changed to `sociomol`.
  - Version set to `0.0.0`.
  - Dash version updated to `2.15.0` for GUI compatibility.
  - Maintainer set to `Long Chen <longleochen91@gmail.com>`.

### Fixed
- Editable install (`pip install -e .`) now works out-of-the-box.
- Dash UI loads correctly without JS/CSS errors.

---

_(Work in progress)_
