# OpenSIN-onboarding Boundaries

## Role
`OpenSIN-onboarding` is the first-run automation and bootstrap layer for OpenSIN setup.

Short version:

- **This repo = onboarding and bootstrap automation**
- **Not this repo = long-term infra canon, product shell, or control-plane truth**

---

## Canonical Ownership

| Concern | Canonical Repo |
|---|---|
| First-run onboarding automation | `OpenSIN-onboarding` |
| Ongoing setup and environment standards | `dev-setup` / `Infra-SIN-Dev-Setup` |
| Product web app | `OpenSIN-WebApp` |
| Internal ops control plane | `ai-agent-system` |
| Official documentation | `OpenSIN-documentation` |
| OpenCode config canon | `upgraded-opencode-stack` |

---

## Hard rules

### 1. First-run only
This repo may automate initial bootstrap, secrets seeding, and first-run setup. It must not become the canonical owner of every long-term environment or infrastructure standard.

### 2. Onboarding flow, not product shell
This repo must not become the main product app, account portal, or control-plane surface.

### 3. Setup alignment, not setup monopoly
This repo should align with setup standards owned elsewhere and link to those standards instead of duplicating all of them indefinitely.
