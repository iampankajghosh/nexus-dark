# Changelog

All notable changes to the "Nexus Dark" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.2] - 2026-01-07

### Added

- Comprehensive code organization with detailed section comments in theme file
- Enhanced token color scopes for better syntax highlighting:
  - JSX/TSX embedded content support
  - Improved operator highlighting
  - Enhanced property and object member support
  - Better namespace and scope highlighting
  - Support for `this` and `super` keywords
  - Markdown syntax improvements (headings, links, code blocks)
  - Symbol and key highlighting
  - Primitive type support
  - Invalid and deprecated code styling

### Changed

- Reorganized theme structure with clear section divisions (Workbench Colors, Token Colors)
- Updated comment color from `#6c708660` to `#585b70` for better visibility
- Improved list hover background from `#262626` to `#404040` for better contrast
- Updated editor diagnostic colors:
  - Error: `#ff5f5f`
  - Warning: `#f0b429`
  - Info: `#7aa2f7`
  - Hint: `#9ece6a`
- Simplified editor diagnostic properties (removed redundant border/background)
- Removed deprecated side bar properties (`sideBarActivityBarTop.border`, `sideBarTitle.background`, `sideBarTitle.border`)
- Moved `semanticHighlighting` property to top of theme configuration for better organization

### Fixed

- Improved token color scope coverage for modern web development
- Better support for React/JSX syntax highlighting
- Enhanced markdown rendering support

## [0.2.1] - 2026-01-06

### Added

- Production-ready documentation and configuration
- Comprehensive installation and usage instructions
- Added .vscodeignore for proper extension packaging

### Changed

- Enhanced README with detailed features, installation methods, and contributing guidelines
- Improved documentation structure for better user experience

## [0.2.0] - 2025-12-28

### Changed

- Improved documentation structure and consistency
- Enhanced package.json with additional metadata (homepage, keywords, author)
- Updated README with VS Code Marketplace direct link
- Standardized CHANGELOG format following Keep a Changelog standards

## [0.1.0] - 2025-01-27

### Added

- Initial release of Nexus Dark
- Modern dark theme with clean aesthetics
- Comprehensive color scheme for editor and UI components
- Support for modern web development syntax highlighting
- Semantic highlighting support
