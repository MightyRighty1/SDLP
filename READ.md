# SDLP Fixture Bundle v4

This repository contains the canonical SDLP fixture bundle for
Object Format‑07 and Lineage‑03, including the EMILIA mapping profile
and the full positive and negative test suite.

These fixtures are used to validate:
- SDLP native provenance and lineage
- EMILIA authority and execution‑admission separation
- Cross‑stack verification between SDLP and EMILIA

The bundle includes:
- 1 native positive case
- 11 single‑axis negative cases
- 1 EMILIA integrity‑only stop
- 1 EMILIA mapped AEC/Gate admission case
- 5 EMILIA refusal cases

The runner reproduces the published SHA‑256 digest, verifies a fresh
Ed25519 test signature, and executes all native and EMILIA cases.

Expected result:

