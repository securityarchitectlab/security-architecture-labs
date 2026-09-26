# Security Architecture Labs

A hands-on laboratory for building and testing Security Architecture patterns.

## Purpose

This repository is for **implementation**, not primarily documentation. Use it to build small, reproducible experiments that turn architecture concepts into working evidence.

Typical content includes:

- Terraform
- Bicep
- Python
- PowerShell
- Mermaid
- PlantUML
- test and validation scripts
- configuration examples
- architecture-as-code
- small disposable lab environments

## Lab discipline

Each lab should state:

1. **Objective** — what is being tested.
2. **Scope** — what the lab does and does not model.
3. **Prerequisites** — tools, versions, credentials or local services.
4. **Architecture** — components, trust boundaries and data flows.
5. **Build** — reproducible implementation steps or code.
6. **Validation** — tests and expected results.
7. **Security considerations** — risks, limitations and unsafe shortcuts.
8. **Teardown** — how to remove resources safely.
9. **Lessons** — what the experiment demonstrates.

Prefer small, disposable environments over production-like complexity. Never commit real credentials, private keys, tokens, certificates containing private material, customer data, or other secrets.

## Relationship to the other repositories

- **security-architect-development** — learning, Northstar, exercises and portfolio evidence.
- **security-architecture-toolkit** — reusable professional patterns and guidance.
- **security-architecture-labs** — working implementations and experiments.

The lab repository can feed evidence back into the development workspace and reusable patterns back into the toolkit.
