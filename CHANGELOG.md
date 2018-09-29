# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.0.4]

### Added

- Adds support for `--info-verbosity verbose` as [webpack/webpack-cli#570](https://github.com/webpack/webpack-cli/issues/570) as been fixed

## [0.0.3]

### Fixed

- Fixes issue (_maybe?_) with matchers conflicting with language services

## [0.0.2]

### Fixed

- Fixes issue **$ts-webpack-watch** not handling absolute paths properly &mdash; Watch out for 🐛[Microsoft/vscode#56721](https://github.com/Microsoft/vscode/issues/56721) if you are basing a problem matcher on another
- Fixes issues with multi-root folders and tslint warnings
- Fixes some issues with errors overlapping with language services

## [0.0.1]

### Added

- Initial release