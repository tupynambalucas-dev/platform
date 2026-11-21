# Changelog - @tupynambalucas-dev/platform

<!-- changelog-start -->

## [1.1.0] - 2026-11-20

### Features & Capabilities

- `platform`
  - [#43](https://github.com/tupynambalucas-dev/platform/pull/43) feat(agents): consume agent-mesh umbrella package via node_modules ([@tupynambalucas](https://github.com/tupynambalucas))
- `k8s`
  - [#40](https://github.com/tupynambalucas-dev/platform/pull/40) feat(k8s): document github app machine identity variables in env template ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#36](https://github.com/tupynambalucas-dev/platform/pull/36) feat(k8s): harden cluster mcp manifests and restore playwright service ([@tupynambalucas](https://github.com/tupynambalucas))

### Refactoring & Internal Architecture

- `k8s`
  - [#41](https://github.com/tupynambalucas-dev/platform/pull/41) refactor(k8s): standardize github app environment variable names in env template ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#35](https://github.com/tupynambalucas-dev/platform/pull/35) refactor(k8s): decommission mcp-playwright from cluster infrastructure ([@tupynambalucas](https://github.com/tupynambalucas))

### Documentation & Specifications

- `platform`
  - [#44](https://github.com/tupynambalucas-dev/platform/pull/44) docs(agents): configure umbrella package catalog and docs ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#48](https://github.com/tupynambalucas-dev/platform/pull/48) docs(agents): document plan dual-storage and register plugins ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#49](https://github.com/tupynambalucas-dev/platform/pull/49) docs(readme): standardize platform monorepo root documentation ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#50](https://github.com/tupynambalucas-dev/platform/pull/50) docs(agents): enforce .agents/plans storage and clean ignore triad ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#53](https://github.com/tupynambalucas-dev/platform/pull/53) docs(changelog): upgrade to keep a changelog format ([@tupynambalucas](https://github.com/tupynambalucas))

### Bug Fixes & Corrections

- `platform`
  - [#34](https://github.com/tupynambalucas-dev/platform/pull/34) fix(vscode): enable deep workspace search indexing without ignore file restrictions ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#51](https://github.com/tupynambalucas-dev/platform/pull/51) fix(ignore): remove trailing wildcard from .ignore and .rgignore ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))

---

## [1.0.0] - 2026-10-03

Welcome to the foundational release of `platform` (`v1.0.0`). This milestone establishes our core architecture, localization infrastructure, and unifies our content strategy.

### Features & Capabilities

- `corporate-web`
  - [49ae855](https://github.com/tupynambalucas-dev/platform/commit/49ae855) feat(content): unify content architecture, merging changelog and blog into a single chronological timeline ([@tupynambalucas](https://github.com/tupynambalucas))
  - [531ad0d](https://github.com/tupynambalucas-dev/platform/commit/531ad0d) feat(localization): enterprise localization pipeline extracting Docusaurus React UI strings into messages/ folder ([@tupynambalucas](https://github.com/tupynambalucas))
  - [dbcba51](https://github.com/tupynambalucas-dev/platform/commit/dbcba51) feat(i18n): deploy unified plugin to automatically unpack Crowdin translations directly into native locale structure ([@tupynambalucas](https://github.com/tupynambalucas))

### Refactoring & Internal Architecture

- `platform`
  - [8a18075](https://github.com/tupynambalucas-dev/platform/commit/8a18075) refactor(crowdin): map Crowdin properties for Docusaurus JSON (`type: chrome`), preventing translators from modifying system keys ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))

[1.1.0]: https://github.com/tupynambalucas-dev/platform/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/tupynambalucas-dev/platform/releases/tag/v1.0.0
