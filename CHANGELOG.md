# Changelog

## [1.0.1] - 2022-08-21

### Changed

- Improve execution time.
- If no lines remain, output an empty string.
  Previously, an excessive line break was added.

## [1.0.0] - 2022-08-19

### Added

- Compress consecutive stars into one.
- Extension icon.
- Usage animation in the README.

## [0.1.1] - 2022-08-08

### Fixed

- Fixed the issue that if the string containing a star to be won
  also contains a question mark, and it appears later, it cannot win.

## [0.1.0] - 2022-08-07

- Initial release
- The precedence between `*` and `?` is unstable.
