# Changelog - tupynambalucas-dev/platform

All notable changes to the `platform` enterprise full-stack monorepo will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- changelog-start -->

## [1.1.0] - 2026-11-20

### Features & Capabilities

- [feat(agents): consume agent-mesh umbrella package via node_modules #43](https://github.com/tupynambalucas-dev/platform/pull/43)
- [feat(k8s): document github app machine identity variables in env template #40](https://github.com/tupynambalucas-dev/platform/pull/40)
- [feat(k8s): harden cluster mcp manifests and restore playwright service #36](https://github.com/tupynambalucas-dev/platform/pull/36)

### Refactoring & Internal Architecture

- [refactor(k8s): standardize github app environment variable names in env template #41](https://github.com/tupynambalucas-dev/platform/pull/41)
- [refactor(k8s): decommission mcp-playwright from cluster infrastructure #35](https://github.com/tupynambalucas-dev/platform/pull/35)

### Documentation & Specifications

- [docs(agents): configure umbrella package catalog and docs #44](https://github.com/tupynambalucas-dev/platform/pull/44)
- [docs(agents): document plan dual-storage and register plugins #48](https://github.com/tupynambalucas-dev/platform/pull/48)
- [docs(readme): standardize platform monorepo root documentation #49](https://github.com/tupynambalucas-dev/platform/pull/49)
- [docs(agents): enforce .agents/plans storage and clean ignore triad #50](https://github.com/tupynambalucas-dev/platform/pull/50)
- [docs(changelog): upgrade to keep a changelog format #53](https://github.com/tupynambalucas-dev/platform/pull/53)

### Bug Fixes & Corrections

- [fix(vscode): enable deep workspace search indexing without ignore file restrictions #34](https://github.com/tupynambalucas-dev/platform/pull/34)
- [fix(ignore): remove trailing wildcard from .ignore and .rgignore #51](https://github.com/tupynambalucas-dev/platform/pull/51)

---

## [1.0.0] - 2026-10-03

Welcome to the foundational release of `platform` (`v1.0.0`). This milestone establishes our core architecture, localization infrastructure, and unifies our content strategy.

### Features & Capabilities

- [feat(content): unify content architecture, merging changelog and blog into a single chronological timeline](https://github.com/tupynambalucas-dev/platform/commit/49ae855)
- [feat(localization): enterprise localization pipeline extracting Docusaurus React UI strings into messages/ folder](https://github.com/tupynambalucas-dev/platform/commit/531ad0d)
- [feat(i18n): deploy unified plugin to automatically unpack Crowdin translations directly into native locale structure](https://github.com/tupynambalucas-dev/platform/commit/dbcba51)

### Refactoring & Internal Architecture

- [refactor(crowdin): map Crowdin properties for Docusaurus JSON (`type: chrome`), preventing translators from modifying system keys](https://github.com/tupynambalucas-dev/platform/commit/8a18075)

[1.1.0]: https://github.com/tupynambalucas-dev/platform/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/tupynambalucas-dev/platform/releases/tag/v1.0.0
