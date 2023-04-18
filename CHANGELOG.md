# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.1] - 2023-04-18

### Fixed

- Rename the symbolic link to this plugin in the Obsidian vault.
- Major update to the internal link parser. #6.
- Modified the behaviour of the markdown post processor. #6.

### Changed

- Update many notes in the Obsidian vault.
- Update the NPM dependencies.

## [1.1.0] - 2023-04-10

### Added

- A settings tab to configure the plugin.
- Shorten internal links to blocks, headings, notes and files.
- Show icons next to internal links to indicate their types.
- Replace external link icons with the icons provided by this plugin.
- Reload the editing and preview view when settings are changed.

### Changed

- Refactor the structure of the plugin.
- Rewrite the internal system to be more generic and robust.
- Update the [`README.md`](./README.md) with new documentation.
- Change the plugin name to be less specific.
- Update GitHub workflow to include `styles.css`.

## [1.0.2] - 2023-01-15

### Fixed

- Show decorations when the rightmost character is selected.
- Don't update decorations when mouse is down in an attempt to mimic Obsidian's behaviour.

## [1.0.1] - 2023-01-15

### Added

- An Obsidian vault to document edge cases.
- A [`CHANGELOG.md`](./CHANGELOG.md).

### Fixed

- Fixed links which contain Markdown formatting. #2.

## [1.0.0] - 2022-12-28

### Added

- The Obsidian extension which is an editor extension and a markdown post-processor.
- A build system to transpile TypeScript to JavaScript.
- A GitHub workflow to publish the extension.
- Project settings for Visual Studio Code.
- A [`README.md`](./README.md) and a [`LICENSE`](./LICENSE).

[1.1.1]: https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings/releases/tag/v1.1.1
[1.1.0]: https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings/releases/tag/v1.1.0
[1.0.2]: https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings/releases/tag/v1.0.2
[1.0.1]: https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings/releases/tag/v1.0.1
[1.0.0]: https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings/releases/tag/v1.0.0
