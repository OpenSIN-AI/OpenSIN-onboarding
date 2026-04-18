# Contributing

## Boundary Rules

Before adding a flow, step, or top-level claim, answer:

1. Is this first-run onboarding, or an ongoing environment/infrastructure standard?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `OpenSIN-onboarding` if:
- it automates first-run setup
- it bootstraps credentials, local prerequisites, or initial integrations
- it improves onboarding verification and handoff

### Do NOT put it in `OpenSIN-onboarding` if:
- it becomes the long-term infra canon
- it becomes the product app or control-plane surface
- it duplicates official docs or config canon
