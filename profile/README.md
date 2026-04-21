# XSAVO

**Building the tools agents need.**

XSAVO is an AI infrastructure lab. We build the interfaces, APIs, and primitives that enable autonomous agents to operate in the physical and digital world.

Every piece of infrastructure that assumes a human operator will need an agent-native interface.

We are moving from "Software as a Service" to "Software as a Co-worker." The underlying plumbing has to change.

---

### Products

| Product | What it does | Status |
| --- | --- | --- |
| **Beacon** | Messaging layer for the agent era. Gives agents a dedicated phone number, persistent conversation memory, contact management, OTP verification, and MCP-native interfaces for human communication. | `Beta Release` |
| **Ledger** | Payments layer for the agent era. Gives agents a wallet they can earn and spend from through non-custodial, multi-rail infrastructure spanning stablecoins, mobile money, and cards. | `Research` |
| **Vault** | Identity and access layer for the agent era. Gives agents scoped, auditable access to tools through credentials, capability tokens, session management, and audit trails. | `Experimental` |

### Why These Products

- **Beacon** handles the full SMS lifecycle for agents: sending, receiving, threading, contacts, verification, and MCP tooling.
- **Ledger** explores how agents can pay and get paid without forcing the world onto a single rail or custody model.
- **Vault** secures the agent runtime itself with scoped credentials, short-lived capabilities, and auditability.

### The Lab

We run agents against real workloads. The gaps we hit become the primitives we ship. Beacon, Ledger, and Vault all started here.

- **Turbine** - our monorepo and build methodology for auth, state, and memory primitives.
- **Dyno** - our internal benchmark for agent reliability and interface quality.
- **Open Research** - protocols, evals, and post-mortems published so teams do not keep rebuilding the same plumbing in isolation.

### Product Principles

- **MCP-first**: the agent interface is the primary interface.
- **Self-hosted**: operators deploy the system on their own infrastructure.
- **Auditable by default**: actions, access, and approvals should be inspectable.
- **Non-custodial where it matters**: infrastructure should orchestrate access, not quietly take control.

### This Repository

This repository is the Laravel + Livewire marketing site for XSAVO. It contains the homepage, product pages, checkout and license portal flows for Beacon, and waitlist capture for Ledger and Vault.

---

<sub>A product lab by <a href="https://apexcode.dev">ApexCode</a> · Mombasa, Kenya · <a href="https://xsavo.com">xsavo.com</a></sub>
