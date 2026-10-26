# Shared Git Utilities

The @tupynambalucas-dev/shared-git workspace contains the standardized Git lifecycle scripts and TypeScript-based commit validation helpers for the platform repository.

## Directory Layout

- scripts/: Contains the cross-platform TypeScript scripts executed by repository root hooks (.husky/).

## Features

- **TypeScript Tooling**: Hook scripts are written in TypeScript and executed via Node/tsx for seamless cross-platform execution (Windows/macOS/Linux).
