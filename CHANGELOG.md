# Changelog

All notable changes to this project will be documented in this file.

## [1.0.5] - 2026-06-05

### Fixed
- Fixed npm package issue where only README.md and CHANGELOG.md were published by removing restrictive `files` field from `package.json`.
- Added null/undefined token check in RecaptchaV3Service to properly handle cases where Google returns no token.
- Added debug console logs to RecaptchaV3Service for better troubleshooting.

## [1.0.1] - 2026-06-05

### Added
- Added GitHub Actions workflow to automate deployment of the playground application to GitHub Pages.
- Added a `build:playground` helper script to `package.json`.

### Fixed
- Fixed schema validation error in `angular.json` by removing the invalid `buildOptimizer` option under `development` configuration.
- Updated `moduleResolution` to `bundler` and added `ignoreDeprecations: "6.0"` in `tsconfig.json` to resolve warnings/errors.
