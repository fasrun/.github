# Fasrun

**Define the rules. Let agents execute within them.**

Fasrun is an open-source control plane for AI coding agents.
It turns constraints into enforceable rules that run before any action is taken — so agents can modify code, run commands, and open pull requests without crossing the boundaries you set.

---

## How it works

You write a Fasfile that declares what an agent is allowed to do, what it must ask for, and what it must never do.
When a coding agent (or a workflow driven by Spec Kit) attempts an action, Fasrun checks it first. Compliant actions proceed. Violations are blocked and recorded.

Your repository stays the source of truth. Rules, decisions, and audit trails live alongside the code.

## Start

- **Self-host**: [fasrun/fasrun](https://github.com/fasrun/fasrun) · AGPL-3.0
One command to install the CLI and begin enforcing rules on your own machine.
- **Hosted**: [Fasrun Cloud](https://fasrun.dev) — coming soon.
The first deliveries are free.

## Check it before you trust it

- Fasrun constrains Fasrun. Every rule and decision in this organization is public.
See the [evidence](https://fasrun.dev/evidence) of how the project governs its own agent runs.
- Outside our repos: Fasrun has been used to enforce constraints on real open-source changes.
(Examples will be linked here as they land.)

## Repositories

- **[fasrun](https://github.com/fasrun/fasrun)**: the engine — rule evaluation, CLI, plugin contracts, and the core runtime guardrails
- **[fasrun-docs](https://github.com/fasrun/fasrun-docs)**: documentation
- **[fasrun-website](https://github.com/fasrun/fasrun-website)**: the site at [fasrun.dev](https://fasrun.dev)
- **[fasrun-design](https://github.com/fasrun/fasrun-design)**: design tokens and brand rules

## Questions

[Open an issue](https://github.com/fasrun/fasrun/issues) · support@fasrun.dev · [@fasrun](https://x.com/fasrun)
