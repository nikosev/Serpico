# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- Support Greek language
  - Remove Greek letters from metacharacters, in order to upload templates
    - "Ω" is replaced with "ῼ"
    - "π" is replaced with "𝜋"
- Support Arial font
  - Replace metacharacters that are not compatible with Arial font
    - "𝜋" is replaced with "Ⱦ"
    - "⁂" is replaced with "ȹ"
    - "ツ" is replaced with "Ʉ"
- Footer
  - Add footer and configuration options for it's contents
