# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0](https://github.com/Oddwarrior/Panasonic-AC-frontend/compare/v1.1.0...v1.2.0) (2026-07-26)


### Features

* add PR comment step to verify-build workflow with commit SHA identification ([5c90384](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/5c90384004b3186094e962f1276ced348190acaf))


### Bug Fixes

* add .dockerignore to exclude build artifacts and sensitive files ([cc80d9a](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/cc80d9a0fa86ced6028a4886400a70d479aadc9d))

## [1.1.0](https://github.com/Oddwarrior/Panasonic-AC-frontend/compare/v1.0.0...v1.1.0) (2026-07-25)


### Features

* add non-blocking Trivy vulnerability scanning to pr-verify workflow ([a0b8038](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/a0b8038a33f8f8d5c1fdde2f37c9fd632c14d7b7))
* migrate docker build and push operations to GitHub Container Registry ([e1ded3a](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/e1ded3a9767bd3a54bfc0b64312328bdf37c1d29))


### Bug Fixes

* update Trivy scanning target to Docker image and standardize SHA tagging in CI workflows ([8875ba6](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/8875ba6e23fcebe05db40f1b139cb554e8ec1a56))

## [1.0.0](https://github.com/Oddwarrior/Panasonic-AC-frontend/compare/v0.6.0...v1.0.0) (2026-07-25)


### ⚠ BREAKING CHANGES

* The API endpoints have been completely restructured and require a new authentication token format.

### Features

* completely overhaul the backend API ([12c7a9e](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/12c7a9ef40e793bfa3a247ea24e4b8734b2ad001))
* enable GHA caching for Docker builds in PR workflows ([3f206d8](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/3f206d8d2254fac403ffa39ce3d1554b6a8c3319))


### Bug Fixes

* remove v prefix from image tag in pr-merge workflow ([046dd29](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/046dd2927796412df036d4f7e1e013d32a40ae28))
* remove v prefix from image tag in pr-merge workflow ([f125b62](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/f125b629040bd4a146772430dcc294b46b0ef06f))

## [0.6.0](https://github.com/Oddwarrior/Panasonic-AC-frontend/compare/v0.5.0...v0.6.0) (2026-07-23)


### Features

* add release please capabilities ([e98735b](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/e98735b713dbbfb8a5b2041945b68d3a2f5f1b72))
* add release please capabilities ([7667dfb](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/7667dfbff52d5c55a07a54ee0900d1c9dbd8e9d7))


### Bug Fixes

* reformat index.html and update document title ([2267cc6](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/2267cc68db9656aff133ec989e2421c517359d4e))
* reformat index.html and update document title ([b60587b](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/b60587bbf2010a36220b0e927a58feda517f18ca))

## [0.5.0](https://github.com/Oddwarrior/Panasonic-AC-frontend/compare/v0.4.0...v0.5.0) (2026-07-23)


### Features

* trigger my first automatic release ([672a7e3](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/672a7e3343c20bcd7e8ba7f6d0904e65df256bc9))
* trigger my first automatic release ([99be34b](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/99be34b7d592137419f4f3ef6ff704174fd2ec47))


### Bug Fixes

* another quick fix for release ([ebf5677](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/ebf567719789a31f667839ae547a6503ace78513))
* another quick fix for release ([02d0c18](https://github.com/Oddwarrior/Panasonic-AC-frontend/commit/02d0c189c87855b6b6185a279af471406a93861c))

---
## [0.3.0]() - 2026-07-24

### Added
- Dockerfile and docker-compose configuration for the frontend.
- CI/CD workflow on PR for Docker image builds.
- Docker image tags on PR merge.

### Changed
- None yet.

### Fixed
- None yet.
