# Change Log

All notable changes to the "Maus" color theme extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Improvements
- Syntax highlight for more languages

## [0.0.7] - 2025-11-14

### refactor: enhance punctuation hierarchy and refine palette

Enhanced code readability through semantic grouping and refined color palette:

- Language support: Enhanced Go and TypeScript/TSX function highlighting
- Refined color palette
  - Strings: #7973E8 → #7363E0
  - Comments: #3C4453 → #394252
  - Gold/constants: #BB901B → #CC9808
  - Yellow/assignments: #C6BD80 → #B8B36E
  - Magenta/control flow: #CF3FAD → #E03FA0
- Punctuation: Semantic grouping
  - Brackets/braces/parentheses: #F770FF
  - Accessors/periods/colons: #1EB897 with TypeScript support
  - Statement terminators: #566176
  - Template expressions: #bf64ff
- Diff editor: Customized git diff visualization
- Updated screen asset

## [0.0.6] - 2025-04-24

### chore: scoped comment, editor, editorOverviewRuler

Added block support for comment highlights, and revised the magenta value for find match.

- Updated screen asset

## [0.0.5] - 2025-03-22

### feat: word, editorOverviewRuler, editorGutter support

Defined visual hiearchy for word, selection, and find match, highlights. Aligned `editorGutter` and `editorOverviewRuler` highlights to v0.0.4 state based colors (e.g., warning, invalid, error, deletion) 

- Updated screen asset
- Revised version reference in README

## [0.0.4] - 2025-03-17

### refactor: enhanced values for red, yellow, gold

- Red: ED8C5E (warning)
- Red.Bright: BF4040 (invalid, error)
- Red.Dark: 861D1D (deleted)
- Yellow: C6BD80 (variable)
- Gold: BB901B (modified)
- Updated screen asset
- Revised version reference in README

## [0.0.3] - 2025-03-16

### feat: add italic to function, keyword, storage

- Improved TypeScript / JavaScript highlighting
- Corrected UI styles
- Updated icon asset
- Updated screen asset
- Included 'Optional Settings' in README

## [0.0.2] - 2025-03-15

### fix: resolved incorrect TSX color values

- Improved install instructions
- Updated icon asset

## [0.0.1] - 2025-03-14

### Initial commit

Add Maus Theme extension files:
- Package JSON and configuration
- Icon and screenshot
- README and LICENSE
