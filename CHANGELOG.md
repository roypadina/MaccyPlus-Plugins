# Changelog

All notable changes to this marketplace are listed here, newest first. The marketplace has no
releases; sections are dated. Each plugin's own version is in its `plugin.json` and in
`marketplace.json`. Format follows [Keep a Changelog](https://keepachangelog.com).

## [Unreleased]

## 2026-10-23

### Added
- README badges, screenshot, MaccyPlus link and a link to the apps website; GitHub social preview
  image; Ko-fi support (`.github/FUNDING.yml`).

## 2026-06-26

### Changed
- Renamed for the MaccyPlus app: plugin ids are now `com.maccyplus.*`, the marketplace id is
  `maccyplus-official`, the repo is `MaccyPlus-Plugins` (package checksums recomputed).
- Docs: install steps clarified (the official marketplace is pre-loaded in the app).

## 2026-06-24

### Added
- Initial marketplace with four plugins, each 1.0.0: `example-has-url` (condition: text has a
  URL), `example-shout` (uppercase + `SHOUT:` prefix), `text-transforms` (trim, UPPERCASE, lowercase,
  strip formatting, fix keyboard layout) and `unwrap-terminal` (joins soft-wrapped terminal text back into one line).
- Authoring, declarative and JavaScript plugin, examples and publishing docs; manifest validation
  CI; MIT license.
