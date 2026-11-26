# AI Architect Studio — Agent Operating Contract

Scope: All repositories under the **AI-Architect-Studio** GitHub Organization (https://frankx.ai/ai-architect).
Brand register: `ai-architect`

## Responsible Agent Team & Governance

| Role | Assigned Owner |
| :--- | :--- |
| **Human Codeowner** | `@frankxai` |
| **Organization Steward** | `steward-enterprise` |
| **Executive Seat** | CTO (Enterprise Architecture) + COO (Estate Operations) |
| **Universal IS** | Business IS,Code IS,Starlight Orchestrator |
| **Council Lead** | starlight-architect,starlight-navigator,starlight-sentinel |
| **Primary Harnesses** | `Claude Code`, `Codex`, `Antigravity` |

## Core Guardrails

1. **Think before coding.** State assumptions and surface tradeoffs. Verify file contents and branch state before writing.
2. **Surgical changes.** Touch only the files required for the active slice. Never overwrite or reset another agent's uncommitted worktree.
3. **Branch and worktree discipline.** Never push directly to `main`. Work on `agent/<harness>/<scope>` in a dedicated worktree and open a **draft** pull request first.
4. **Maker != Checker.** The harness that authors a pull request never approves or merges its own pull request.
5. **CI budget discipline.** Keep pull requests in draft until local verification (`lint`, `typecheck`, `test`, `build`) passes. Mark ready for review once.
6. **Non-waivable safety.**
   - Never commit secrets, API keys, or `.env` files.
   - Preserve repository visibility parity: never copy or mirror private repository contents into a public repository.
   - Money fails closed; no autonomous spend or paid API provisioning without explicit human approval.
   - In health and mind domains, model observations only; never diagnose or make clinical claims.

## Federated Repository Roster (7 repositories)

| Repository | Visibility | Primary Owner | Role |
| :--- | :--- | :--- | :--- |
| `ai-architect` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/ai-architect) |
| `ai-coe` | `public` | `frankxai` | canonical repository (former frankxai/ai-coe URL redirects here) |
| `agentic-architecture-field-guide` | `public` | `frankxai` | canonical repository (former frankxai/agentic-architecture-field-guide URL redirects here) |
| `awesome-ai-coe` | `public` | `frankxai` | canonical repository (former frankxai/awesome-ai-coe URL redirects here) |
| `awesome-agent-operating-systems` | `public` | `frankxai` | canonical repository (former frankxai/awesome-agent-operating-systems URL redirects here) |
| `agentic-operating-system-standard` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/agentic-operating-system-standard) |
| `agentic-ops` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/agentic-ops) |

Before proposing a change, resolve the GitHub repository ID. A transferred URL can name the same repository; a mirror has a different ID. Edit the canonical repository and keep retirement archives read-only.

Built on SIP
