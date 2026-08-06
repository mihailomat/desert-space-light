# Change Log

All notable changes to the "desert-space-light" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.2.0] - 2026-08-06

### Fixed

- Give the active find match a real border. It was set to the same color as its own fill, so the match had no visible outline at all.
- Raise scrollbar and minimap slider visibility. Both sat at half the opacity of the editor default and nearly disappeared against the background.
- Improve contrast of word and selection highlights. Their base tones were too close to the background to register, at any opacity.
- Give inactive find matches a faint tint of their own instead of relying entirely on their border.

### Changed

- Distinguish read and write occurrences of the symbol under the cursor. They were previously the same color.
- Add hover and drag states for the scrollbar and minimap sliders, which until now fell back to a cool grey that clashed with the warm chrome.
- Add a background for the "find in selection" range.
- Document every color the theme uses in the readme, including the terminal-only tones, and correct the entries whose described usage no longer matched the theme.
- Retire `#D4E4D1` and `#FCEBD5`, which the highlight rework left unused.

## [1.1.1] - 2026-05-22

### Fixed

- Added a nicer theme icon that both new and potential users can enjoy.

## [1.1.0] - 2026-05-22

### Fixed

- Update find match background and border colors for better visibility.
- Add missing foreground color for editor selection.
- Update language constants scope to remove `variable.language`.
- Update markup token names and add foreground color for bold and italic styles.
- Correct scope for `constant.language` token in theme settings.
- Remove wrong token color for sand creature amber in theme settings.
- Remove alpha channel from background color in theme settings.
- Lower the VSCode engine version to widen compatibility.
- Add bugs URL to package.json for issue tracking.

### Changed

- Improve contrast of disabled Navigation Controls in Command Center.
- Remove background color where it is not yet supported.
- Resolve deprecated theme properties.
- Adapt manifest keywords and gallery banner color.

## [1.0.0] - 2026-03-29

- Initial release
