# Changelog

All notable changes to the "Nexus Dark" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.4] - 2026-01-09

### Added

- Comprehensive terminal color scheme with ANSI color support:
  - Custom terminal background and foreground colors
  - Terminal cursor colors for better visibility
  - Full ANSI color palette (black, red, green, yellow, blue, magenta, cyan, white) with bright variants
  - Terminal selection background color

### Changed

- **Background Color Standardization**: Updated all UI element backgrounds from `#0a0a0a` to `#0c0c0c` for better consistency across:
  - Activity bar, side bar, editor, tabs, editor groups, minimap, editor gutter, overview ruler, breadcrumbs, status bar, title bar, panel, and diff editor
- **Editor Foreground Visibility**: Improved editor foreground color from semi-transparent (`#fafafa80`) to fully opaque (`#fafafa`) for better text readability
- **Line Number Visibility**: Enhanced line number colors:
  - Active line numbers: `#fafafa40` → `#fafafa80`
  - Dimmed line numbers: `#fafafa20` → `#fafafa50`
- **Editor Selection & Highlights**: Improved selection and highlight visibility:
  - Selection background: `#fafafa20` → `#fafafa25`
  - Word highlight backgrounds and borders increased opacity for better visibility
  - Range and symbol highlight backgrounds: `#ffffff10` → `#ffffff15`
  - Range and symbol highlight borders: `#ffffff00` → `#ffffff20`
- **Line Highlighting**: Enhanced active and inactive line highlight backgrounds for better visibility
- **Indent Guides**: Improved indent guide visibility:
  - Background: `#ffffff15` → `#ffffff20`
  - Active background: `#ffffff30` → `#ffffff40`
- **Inlay Hints & Code Lens**: Increased visibility of inlay hints and code lens (`#fafafa60` → `#fafafa80`)
- **Editor Gutter**: Enhanced gutter element visibility:
  - Comment range foreground: `#fafafa40` → `#fafafa60`
  - Comment glyph foreground: `#fafafa80` → `#fafafa`
  - Folding control foreground: `#fafafa80` → `#fafafa`
  - Comment draft glyph: `#fafafa60` → `#fafafa80`
- **Editor Whitespace**: Improved whitespace indicator visibility (`#fafafa20` → `#fafafa30`)
- **Editor Ruler**: Enhanced ruler visibility (`#ffffff10` → `#ffffff20`)
- **Side Bar**: Improved side bar foreground visibility (`#fafafa80` → `#fafafacc`)
- **Breadcrumbs**: Enhanced breadcrumb foreground visibility (`#fafafa80` → `#fafafacc`)
- **Status Bar**: 
  - Updated debugging colors from purple theme to orange theme for better contrast
  - Improved status bar item backgrounds and hover states for better visibility
  - Enhanced status bar foreground visibility (`#fafafa80` → `#fafafacc`)
- **Title Bar**: Improved title bar foreground visibility
- **Panel**: Enhanced panel title inactive foreground (`#fafafa60` → `#fafafa80`)
- **List Elements**: Improved list deemphasized foreground visibility (`#fafafa60` → `#fafafa80`)
- **Input Fields**: Enhanced input placeholder text visibility (`#fafafa60` → `#fafafa80`)
- **Inline Chat**: Improved inline chat input placeholder visibility (`#fafafa60` → `#fafafa80`)
- **Editor Widgets**: Enhanced suggest widget status foreground (`#fafafa60` → `#fafafa80`)
- **Border Colors**: Updated border colors for better consistency (`#0a0a0a` → `#0c0c0c` for contrast borders, window borders, and scrollbar shadow)
- **Focus Border**: Enhanced focus border visibility (`#ffffff08` → `#ffffff30`) for better focus indication
- **Fold Placeholder**: Improved fold placeholder foreground visibility (`#fafafa60` → `#fafafa80`)
- Updated documentation to reflect current version and ensure consistency across all files
- Fixed version mismatch between README.md and package.json

## [0.2.3] - 2026-01-08

### Changed

- Improved general foreground color visibility (from semi-transparent to fully opaque)
- Enhanced scrollbar appearance with transparent background for cleaner look
- Refined list hover background for better contrast and visibility
- Increased minimap foreground opacity for improved code visibility
- Updated editor selection background to a more subtle, neutral color
- Improved inactive selection background for better visual distinction
- Enhanced indent guide visibility for better code structure recognition
- Updated status bar debugging colors from purple to orange theme for better contrast
- Improved comment color visibility (`#585b70` → `#7f849c`) for better readability

### Added

- Support for `.env` file syntax highlighting with distinct colors for variable keys and values

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
