# AI Agents Configuration Hub (`.agents`)

The `.agents/` directory is the Bounded Context for AI behavior customization, tool integration, and knowledge routing within the `platform` monorepo.

---

## Architecture & Integration

Our AI agent configuration combines local domain plugins with the enterprise `@tupynambalucas-dev/agent-mesh` umbrella package:

### 1. Plugin Discovery Manifest (`plugins.json`)

```json
{
  "entries": [
    {
      "path": "./plugins/k8s"
    },
    {
      "path": "node_modules/@tupynambalucas-dev/agent-mesh/plugins/packages"
    }
  ]
}
```

- **`./plugins/k8s`**: Local Kubernetes infrastructure plugin providing the `k8s-docs-architect` and `k8s-docs-auditor` skills.
- **`node_modules/@tupynambalucas-dev/agent-mesh/plugins/packages`**: Upstream organizational plugins (`appsheet`, `atelier`, `docusaurus`, `github-flow`, `github-org`, `gwork`, `repo`, `research`, `secrets`, `web`).

### 2. Dependency Management

The `@tupynambalucas-dev/agent-mesh` package is pinned via `plugins-stack` in [`pnpm-workspace.yaml`](../pnpm-workspace.yaml) and installed via the root [`package.json`](../package.json):

```yaml
catalogs:
  plugins-stack:
    '@tupynambalucas-dev/agent-mesh': 'github:tupynambalucas-dev/agent-mesh'
```

### 3. Sovereign MCP Launchers

MCP servers bundled in `@tupynambalucas-dev/agent-mesh` execute via self-contained launchers (`scripts/launcher.cjs`) without requiring build steps or runtime dependency resolutions from the consumer project.

---

## Directory Layout

- [plugins.json](./plugins.json): Runtime plugin discovery manifest.
- [AGENTS.md](./AGENTS.md): Bounded context router for `.agents/`.
- [plugins/](./plugins/): Local monorepo-specific plugins (`k8s`).
- [rules/](./rules/): Local rule definitions.
- [skills/](./skills/): Local on-demand skills.
- [scripts/](./scripts/): Agent utility scripts.
- [plans/](./plans/): Refactoring and execution plan artifacts.

---

## Navigation

- Parent Workspace: [Platform Monorepo Root](../README.md)
