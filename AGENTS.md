# tupynambalucas.dev Agents Context

This document serves as the root context router for AI agents operating in the
`tupynambalucas-dev/platform` monorepo.

## Navigation

- [README.md](./README.md): Official developer entry point and technical architecture.
- [.agents](./.agents/AGENTS.md): Authoritative domain for agentic AI configurations, skills, and plugins.
- [hub](./hub/AGENTS.md): Internal team context grouping `observability`, `network`, `tools`, `studio`, and `cortex`.
- [corporate](./corporate/AGENTS.md): Public-facing products context housing company website and API.
- [k8s](./k8s/AGENTS.md): Core infrastructure manifests organized by environment overlays (`dev`, `staging`, `prod`).
- [renderer](./renderer/AGENTS.md): Dynamic asset generator and document compilation engine.
- [shared](./shared/AGENTS.md): Cross-workspace utilities, global configurations, and Git hooks.
- [tools](./tools/AGENTS.md): GitHub CLI automation, provisioning scripts, and containerized Git environments.
- [agent-mesh](../agent-mesh/AGENTS.md): Shared AI agent governance and MCP connectors (via `org-core`).

## Architecture

The monorepo uses Skaffold v4beta11 for local development (`dev` environment) across two isolated k3d clusters, configured in the `k8s/` directory:

- `root` ([k8s/skaffold.yaml](./k8s/skaffold.yaml)): Main orchestrator that requires the two modules below.
- `hub` ([k8s/skaffold.hub.yaml](./k8s/skaffold.hub.yaml)): Deploys internal tools to the `k3d-hub` cluster.
- `corporate` ([k8s/skaffold.corporate.yaml](./k8s/skaffold.corporate.yaml)): Deploys public products to the `k3d-corporate` cluster.

Cloud environments (`staging` and `prod`) are delivered via ArgoCD GitOps, circumventing Skaffold entirely.

## Scoped Guardrails

- MUST maintain a strict senior, objective, and technical tone in all communications, logs, and documentation.
- MUST avoid preambles, introductory chatter, conversational filler, or conclusion summaries.
- MUST conduct all conversational chat responses in Brazilian Portuguese (pt-BR).
- MUST write all code, configuration, technical documentation, commit messages, and Markdown files in English (en-US).
- MUST NOT use emojis in any conversational response, chat message, technical document, README, or skill file.
- MUST NOT use placeholders (e.g., TODO, TBD).
- MUST sign all Git commits with SSH: `git commit -S -m "..."`.
- MUST use relative paths for all Markdown links. Absolute filesystem paths are strictly forbidden.
- MUST format all files according to Prettier standards (2-space indent, max 100-character line width).
- MUST hardcode the project name and domain in all `AGENTS.md` and `README.md` files (e.g., `tupynambalucas.dev`).
- **Secret Hygiene**: Secrets are resolved via Infisical (`infisical run --projectId ... --env dev`) or local `.env` fallback. Plaintext tokens must never be logged or committed.
- **Routing**: When working within a specific bounded context, agents MUST read the local `AGENTS.md` file within that directory before proceeding.

## Required Skills

When performing documentation tasks in this monorepo, agents MUST activate the appropriate skill by name before beginning:

- **`agent-router-expert`**: Active when creating, updating, or reviewing any `AGENTS.md` file anywhere in the monorepo.
- **`markdown-expert`**: Active when creating, updating, or reviewing any `README.md`, `.md` skill file, or general Markdown document.
- **`secrets-expert`**: Active when configuring or verifying Infisical secrets or Kubernetes secret manifests.
