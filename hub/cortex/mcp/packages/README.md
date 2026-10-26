# Cortex MCP Standalone Packages

This directory contains reusable, publishable Model Context Protocol (MCP) packages for the
`tupynambalucas.dev` platform architecture.

---

## 1. Role in the Architecture

Packages hosted in this directory are the **Single Source of Truth (SSOT)** for MCP tool implementations:

- Published to GitHub Packages under the scope `@tupynambalucas-dev/cortex-mcp-*`.
- Built with TypeScript and `@modelcontextprotocol/sdk`.
- Configured with standalone `"bin"` CLI entrypoints to execute over standard I/O (stdio).
- Consumed by Antigravity plugins in `agent-mesh` via `pnpm dlx`.
- Packaged as containerized microservices in `../services/` for Kubernetes cluster deployment behind `agentgateway`.

---

## 2. Directory Layout

- `mcp-github/`: GitHub App-authenticated operator (`@tupynambalucas-dev/cortex-mcp-github`).
- `mcp-firecrawl/`: High-fidelity web crawling and scraping tools (`@tupynambalucas-dev/cortex-mcp-firecrawl`).
- `mcp-context7/`: Real-time framework documentation and code snippets (`@tupynambalucas-dev/cortex-mcp-context7`).
- `mcp-memory/`: Semantic vector RAG retrieval and entity graphs (`@tupynambalucas-dev/cortex-mcp-memory`).
- `mcp-appsheet/`: AppSheet REST API database mutation and querying (`@tupynambalucas-dev/cortex-mcp-appsheet`).
- `mcp-google-workspace/`: Google Sheets, Drive, and Docs automation (`@tupynambalucas-dev/cortex-mcp-gwork`).
