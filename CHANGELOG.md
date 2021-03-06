# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]
- Update for set of flags
- New Sitemap Module
- Do not define page title by page name, when title field is empty
- Define keywords on Multilingual Pages

## [2.1.0] - t.b.r.
### Added
- Added support for regional language codes (e.g. de-CH).

### Fixed
- Fixed issue where alias of default language was picked for alternative languages when site was entered on root (/).

## [2.0.0-beta2] - 2018-04-19
### Added
- Added more detailed installation instructions including configuration step.

### Changed
- Moved replaceInsertTags hook to its own class.

### Fixed
- Fixed bug in PageI18nl10nRegular.php that prevented ESI tags from getting rendered when cache is active.
- Fixed from asset path for extension's CSS files.

## [2.0.0-beta] - 2018-01-27
### Added
- Tests and lints by @ClaudioDeFacci.

### Changed
- Refactored extension to work in Contao 4.4.7 by @ClaudioDeFacci.
- Created compatibility with PHP 7 by @ClaudioDeFacci.

### Removed
- Removed support for Isotope by @ClaudioDeFacci.

## [1.5] - 2015
### Added
- Define languages based on Contao root site structure settings
- Module to switch languages in frontend
- Compatibility with multidomain environments
- Compatibility with isotope (1.3.1)
- Articles section
    - Define language for each content element
    - Possibility to choose Neutral language (shows for all languages)
    - Filter for specific language content elements
- Multilingual Pages section
    - Define visibility
    - Define titles
    - Define alias
    - Define description
    - Define Localized date and time settings
    - Generate all missing multilingual pages
- Site structure
    - Automatically generate multilingual pages (Publish L10N)
    - Button for editing the Multilingual pages (doesn't work, just links to MP section)
