---
trigger: always_on
---

# Kubernetes Infrastructure Domain Rules

0. Autonomous Domain Mandate:
   - When requested to create, modify, inspect, or audit Kubernetes manifests, Helm values, Kustomize overlays, or cluster GitOps documentation, the agent MUST autonomously engage the k8s skills (`k8s-docs-auditor`, `k8s-docs-architect`) without waiting for explicit skill invocations from the user.

1. Diataxis Framework Standard:
   - GitOps infrastructure documentation MUST adhere strictly to the Diataxis quadrants: `tutorials/`, `how-to-guides/`, `reference/`, and `explanation/`.
   - Never place task guides in a generic `guides/` folder; use `how-to-guides/`.

2. Zero-Emoji Invariant:
   - Emojis are strictly prohibited across all manifests, YAML comments, documentation, and agent output.

3. Technical Language Policy:
   - All manifests, architectural documentation, and configuration files must be authored strictly in en-US.
