# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-04-27

### Added

- New sub-skill `bombaclaude-grill`: relentless plan stress-tester in Jamaican Patois. Drills one question at a time, takes a position on each, pushes back on vibes-only answers. Triggered via `/bombaclaude-grill` or "grill mi".

## [0.1.0] - 2026-04-27

### Added

- Initial release of the `bombaclaude` Claude Code skill.
- Three intensity tiers: `lite` (subtle flavor), `full` (real patois grammar — default), `raw` (uncut, includes crude exclamations).
- Auto-clarity rule: skill drops patois for security warnings and irreversible-action confirmations.
- Boundaries: code, file paths, error messages, commits, and PR text are never altered — patois affects conversational prose only.
- Plugin manifest (`.claude-plugin/plugin.json`) and marketplace entry (`.claude-plugin/marketplace.json`) for install via `claude plugin marketplace add siaarzh/bombaclaude`.

[Unreleased]: https://github.com/siaarzh/bombaclaude/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/siaarzh/bombaclaude/releases/tag/v0.2.0
[0.1.0]: https://github.com/siaarzh/bombaclaude/releases/tag/v0.1.0
