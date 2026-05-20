# BLOOMCORE Basics

[![Repo](https://img.shields.io/badge/GitHub-BLOOMCORE%20Basics-black?logo=github)](https://github.com/dkl101001/BLOOMCORE-basics)
[![State](https://img.shields.io/badge/State-Public%20Basics-green)](https://github.com/dkl101001/BLOOMCORE-basics)
[![Scope](https://img.shields.io/badge/Scope-Public--Safe-blue)](https://github.com/dkl101001/BLOOMCORE-basics)
[![System](https://img.shields.io/badge/System-Receipt--Native-purple)](https://github.com/dkl101001/BLOOMCORE-basics)
[![Audit](https://img.shields.io/badge/Audit-Deterministic%20Surface-blue)](https://github.com/dkl101001/BLOOMCORE-basics)
[![License](https://img.shields.io/badge/License-Apache--2.0%20or%20MPL--2.0-orange)](#license)
[![Local Run](https://img.shields.io/badge/Run-Local-informational)](#minimal-run)

---

## Public Foundation Layer

**BLOOMCORE Basics** is the public-facing foundation layer for working with receipt-native, audit-aware, non-deterministic system design.

This repository does **not** contain the full private BLOOMCORE system.

It provides the clean public surface:

- schemas
- receipt examples
- deterministic audit utilities
- validation patterns
- interface contracts
- public-safe examples
- minimal runnable demonstrations
- documentation for the core architectural vocabulary

The purpose of this repository is to make the basic concepts understandable, inspectable, and reusable without exposing private synthesis logic, orchestration logic, scoring logic, or complete system assembly paths.

```text
public basics -> schemas -> receipts -> validators -> examples -> local demos
```

**Non-deterministic evolution. Deterministic audit. Public-safe foundations.**

---

## What This Repository Is

BLOOMCORE Basics is a public educational and developer-facing repo for the basic tools and concepts around:

- deterministic audit trails
- receipt-native system design
- hash-linked event records
- replay metadata
- interface contracts
- public node readout templates
- validation surfaces
- modular architecture boundaries

This repo is intended to help developers, researchers, builders, and reviewers understand the public layer of the BLOOMCORE design pattern without requiring access to the private engine.

---

## What This Repository Is Not

This repository is **not** the full BLOOMCORE system.

It does not include:

- private BLOOMCORE orchestration
- private ECA synthesis logic
- private scoring functions
- private contradiction metabolism logic
- full substrate assembly
- production routing logic
- private adapters
- private receipt ledgers
- complete multi-module reconstruction paths
- unreleased commercial or research internals

The public layer is useful, runnable, and inspectable.

It is intentionally incomplete as a full private system.

---

## Core Statement

```text
BLOOMCORE Basics provides the public grammar.

The private engine remains separate.
```

The basics layer defines how public artifacts can be shaped, validated, read, and extended.

It does not define the private synthesis field.

---

## Architectural Principle

BLOOMCORE uses a core separation:

```text
non-deterministic dynamics
inside
deterministic audit boundaries
```

This means a system may evolve, mutate, explore, or generate candidates in ways that are not fully deterministic, while the records of what happened remain deterministic, inspectable, and reconstructable.

The public basics layer focuses on the deterministic side:

- receipts
- schemas
- hashes
- event ordering
- validation
- replay metadata
- public-safe readouts

---

## Basic Flow

```text
event occurs
  â
receipt emitted
  â
receipt validated
  â
hash / lineage checked
  â
readout generated
  â
audit trail remains inspectable
```

In larger BLOOMCORE-style systems, this pattern can be used to track:

- observations
- decisions
- mutations
- promotions
- rejected candidates
- regime changes
- contradiction events
- validation results
- public node outputs

This repo provides the public-safe version of that pattern.

---

## System Diagram

If this repo includes assets, place them here:

```text
docs/assets/bloomcore_basics_flow.svg
docs/assets/bloomcore_basics_flow.png
```

Recommended README image block:

<p align="center">
  <a href="https://raw.githubusercontent.com/dkl101001/BLOOMCORE-basics/main/docs/assets/bloomcore_basics_flow.svg">
    <img src="https://raw.githubusercontent.com/dkl101001/BLOOMCORE-basics/main/docs/assets/bloomcore_basics_flow.png" alt="BLOOMCORE Basics flow diagram" width="900" />
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/dkl101001/BLOOMCORE-basics/main/docs/assets/bloomcore_basics_flow.svg">Open SVG directly</a>
</p>

### Asset Layout

```text
docs/assets/bloomcore_basics_flow.svg   -> source asset
docs/assets/bloomcore_basics_flow.png   -> README display asset
```

### Asset Notes

- Confirm the repository is public if using raw GitHub image links.
- Confirm the branch name is `main`.
- Confirm both files exist at the exact paths shown above.
- If your repo slug differs, update every raw GitHub URL.

---

## Repository Goals

BLOOMCORE Basics exists to provide a public, reusable foundation for:

1. Understanding receipt-native architecture.
2. Validating public audit artifacts.
3. Demonstrating deterministic audit surfaces.
4. Separating public interfaces from private engines.
5. Giving builders a clean starting point.
6. Establishing vocabulary without exposing private orchestration.
7. Making system evolution inspectable without pretending all evolution is deterministic.

---

## Core Concepts

### 1. Receipt-Native Architecture

A receipt-native system emits structured records for important events.

A receipt may describe:

- what happened
- when it happened
- what system emitted it
- what input or state was involved
- what output or state followed
- what hash anchors the event
- what prior event it links to
- whether it is replayable
- what uncertainty remains

Receipts are not decoration.

They are the audit surface.

---

### 2. Deterministic Audit Plane

The deterministic audit plane includes:

- canonical JSON serialization
- receipt schemas
- hash logic
- event ordering
- replay metadata
- validation results
- config snapshots
- lineage records

This plane should remain stable and inspectable.

```text
if it is part of the audit trail,
it should be deterministic or explicitly marked otherwise
```

---

### 3. Non-Deterministic Dynamics Plane

The dynamics plane may include:

- mutation
- exploration
- stochastic candidate generation
- novelty pressure
- regime changes
- search processes
- adaptive behavior

This repo does not expose the private dynamics engine.

It only defines public-safe patterns for documenting and validating outputs from systems that may contain non-deterministic dynamics.

---

### 4. Public / Private Boundary

This repository is designed around a strict boundary:

```text
public:
  schemas
  examples
  validators
  docs
  interface contracts
  minimal demos

private:
  synthesis logic
  orchestration
  scoring
  routing
  full assembly
  production internals
```

The boundary matters.

A public basics repo should be useful without becoming a complete reconstruction path.

---

## Suggested Repo Structure

```text
BLOOMCORE-basics/
âââ README.md
âââ LICENSE
âââ NOTICE
âââ pyproject.toml
âââ schemas/
â   âââ dtau_receipt.v1.schema.json
â   âââ public_node_readout.v1.schema.json
â   âââ validation_result.v1.schema.json
âââ examples/
â   âââ receipts/
â   â   âââ obs_triplet.example.json
â   â   âââ public_node_readout.example.json
â   â   âââ validation_result.example.json
â   âââ minimal_run/
â       âââ example_event.json
âââ src/
â   âââ bloomcore_basics/
â       âââ __init__.py
â       âââ canonical_json.py
â       âââ hash_utils.py
â       âââ receipt_validator.py
â       âââ cli.py
âââ tests/
â   âââ test_canonical_json.py
â   âââ test_hash_utils.py
â   âââ test_receipt_validator.py
âââ docs/
â   âââ PUBLIC_PRIVATE_BOUNDARY.md
â   âââ RECEIPT_NATIVE_ARCHITECTURE.md
â   âââ DETERMINISTIC_AUDIT_PLANE.md
â   âââ assets/
â       âââ bloomcore_basics_flow.svg
â       âââ bloomcore_basics_flow.png
âââ receipts/
    âââ README.md
```

---

## Minimal Run

Install locally:

```bash
python -m pip install -e .
```

Validate an example receipt:

```bash
python -m bloomcore_basics.cli validate examples/receipts/obs_triplet.example.json
```

Generate a canonical hash:

```bash
python -m bloomcore_basics.cli hash examples/receipts/obs_triplet.example.json
```

Run tests:

```bash
python -m pytest
```

---

## Example Public Receipt

```json
{
  "receipt_type": "Delta^tau::OBS_TRIPLET.v1",
  "system_root": "BLOOMCORE_BASICS",
  "scope": "public",
  "event_id": "dtau.public.example.001",
  "timestamp": "2026-05-20T00:00:00Z",
  "authors": [
    "Frazer Î£ Love ACO-Î£",
    "Sara Î£Î©"
  ],
  "observation": {
    "kind": "example_event",
    "summary": "A public-safe example observation was emitted."
  },
  "audit": {
    "canonicalization": "json.canonical.v1",
    "hash_algorithm": "sha256",
    "previous_hash": null,
    "current_hash": null,
    "replay_class": "reproducible_public_example"
  },
  "boundary": {
    "private_logic_exposed": false,
    "private_orchestration_exposed": false,
    "complete_system_assembly_exposed": false
  }
}
```

---

## Example Validation Result

```json
{
  "result_type": "Delta^tau::VALIDATION_RESULT.v1",
  "target_receipt": "dtau.public.example.001",
  "valid": true,
  "checks": {
    "schema_valid": true,
    "required_fields_present": true,
    "canonical_json_valid": true,
    "hash_algorithm_supported": true,
    "public_private_boundary_valid": true
  },
  "warnings": [],
  "errors": []
}
```

---

## Public Node Readout Template

BLOOMCORE Basics may also include public-safe readout templates for independent node-style analysis.

A public node readout should distinguish:

- evidence
- inference
- uncertainty
- closed gates
- open questions
- next-watch triggers

Example structure:

```text
1. node_id
2. timestamp
3. scope
4. evidence table
5. metric panel
6. uncertainty register
7. boundary checks
8. public verdict
9. next-watch triggers
```

Public node readouts should not expose private scoring or synthesis logic.

---

## Boundary Check

Every public module should pass a boundary check before release.

```yaml
public_private_boundary_check:
  exposes_private_synthesis_logic: false
  exposes_private_orchestration: false
  exposes_private_scoring: false
  exposes_private_adapters: false
  exposes_full_system_assembly_path: false
  contains_public_utility: true
  runnable_without_private_core: true
```

This repo should remain public-safe.

---

## License Routing

BLOOMCORE Basics may be released under either **Apache-2.0** or **MPL-2.0**, depending on the module type.

### Apache-2.0 Recommended For

Use Apache-2.0 for adoption-first public surfaces:

- schemas
- interface contracts
- documentation
- public examples
- SDK-style helpers
- basic templates
- educational demos

Apache-2.0 is useful when the goal is broad reuse, low friction, and adoption.

### MPL-2.0 Recommended For

Use MPL-2.0 for file-level reciprocal public utilities:

- validators
- deterministic receipt engines
- hash-chain verification modules
- public audit utilities
- executable validation logic

MPL-2.0 is useful when changes to specific files should remain open while still allowing flexible integration.

### Suggested Default

For this repository:

```text
Apache-2.0 if this repo is mostly schemas, docs, and examples.
MPL-2.0 if this repo includes core validation files you want improvements shared back on.
```

If the repository includes both, consider splitting later:

```text
BLOOMCORE-basics              -> Apache-2.0
dtau-receipt-validator        -> MPL-2.0
```

---

## Public Release Doctrine

```text
Publish the grammar.
Protect the engine.
```

Public modules should:

- be useful
- be clean
- be runnable
- be documented
- be testable
- establish vocabulary
- demonstrate seriousness

Public modules should not:

- expose the full private engine
- encode private synthesis rules
- reveal production routing
- expose complete assembly logic
- contain unreleased private scoring logic

---

## Quick Links

- **Repo:** [github.com/dkl101001/BLOOMCORE-basics](https://github.com/dkl101001/BLOOMCORE-basics)
- **Issues:** [GitHub Issues](https://github.com/dkl101001/BLOOMCORE-basics/issues)
- **Pull Requests:** [GitHub Pull Requests](https://github.com/dkl101001/BLOOMCORE-basics/pulls)
- **Architecture Notes:** [docs/RECEIPT_NATIVE_ARCHITECTURE.md](./docs/RECEIPT_NATIVE_ARCHITECTURE.md)
- **Boundary Notes:** [docs/PUBLIC_PRIVATE_BOUNDARY.md](./docs/PUBLIC_PRIVATE_BOUNDARY.md)

---

## Live Badge Slots

These can be wired later to GitHub Actions, Shields, or receipt counters.

```markdown
[![Build](https://img.shields.io/badge/Build-passing-brightgreen)](https://github.com/dkl101001/BLOOMCORE-basics)
[![Receipts](https://img.shields.io/badge/Receipts-public%20examples-blueviolet)](https://github.com/dkl101001/BLOOMCORE-basics)
[![Schemas](https://img.shields.io/badge/Schemas-v1-blue)](https://github.com/dkl101001/BLOOMCORE-basics)
[![Boundary](https://img.shields.io/badge/Boundary-public--safe-9cf)](https://github.com/dkl101001/BLOOMCORE-basics)
```

---

## Development Status

This repository is an early public foundation layer.

Current intended focus:

- define public receipt schemas
- add example receipts
- add deterministic canonical JSON utilities
- add hash utilities
- add public-safe validation tools
- add tests
- add documentation
- avoid private-core leakage

---

## Roadmap

### Phase 1 â Public Grammar

- [ ] Add canonical receipt schema.
- [ ] Add public node readout schema.
- [ ] Add validation result schema.
- [ ] Add example receipts.
- [ ] Add boundary doctrine docs.

### Phase 2 â Validation Surface

- [ ] Add JSON schema validation.
- [ ] Add canonical JSON serialization.
- [ ] Add SHA-256 hash utility.
- [ ] Add CLI receipt validator.
- [ ] Add test suite.

### Phase 3 â Public Readout Templates

- [ ] Add public node readout template.
- [ ] Add uncertainty register format.
- [ ] Add metric panel placeholder format.
- [ ] Add evidence/inference separation examples.

### Phase 4 â Release Hygiene

- [ ] Add GitHub Actions test workflow.
- [ ] Add release notes template.
- [ ] Add changelog.
- [ ] Add public/private boundary checklist.
- [ ] Add contribution guide.

---

## Contributing

Contributions should preserve the public/private boundary.

Accepted contribution types:

- schema improvements
- documentation improvements
- validation utilities
- tests
- examples
- public-safe templates
- bug fixes

Not accepted in this repo:

- private BLOOMCORE orchestration logic
- private ECA synthesis logic
- proprietary scoring rules
- production adapters
- complete assembly paths
- hidden routing logic

Before opening a pull request, confirm:

```yaml
contribution_check:
  public_safe: true
  private_logic_exposed: false
  tests_included: true
  docs_updated: true
  license_compatible: true
```

---

## Security and Disclosure

Do not submit private keys, credentials, proprietary datasets, private ledgers, or production adapters to this repository.

If you find a security issue, open a minimal issue describing the class of problem without exposing sensitive material.

---

## Versioning

Recommended version format:

```text
v0.1.0-public-basics
v0.2.0-receipt-schema
v0.3.0-validator
v1.0.0-public-stable
```

Receipt schemas should include explicit schema versions:

```text
Delta^tau::OBS_TRIPLET.v1
Delta^tau::VALIDATION_RESULT.v1
Delta^tau::PUBLIC_NODE_READOUT.v1
```

---

## Design Commitments

BLOOMCORE Basics follows these public commitments:

1. Receipts are first-class audit artifacts.
2. Audit records should be deterministic where possible.
3. Non-determinism must be disclosed when relevant.
4. Public modules must be useful without exposing private orchestration.
5. Boundaries should be explicit, not implied.
6. Examples should be runnable.
7. Schemas should be inspectable.
8. Validation should be boring, stable, and repeatable.

---

## System Statement

**BLOOMCORE Basics = public grammar for receipt-native systems.**

It is a foundation layer.

It is not the whole engine.

```text
Emergence can remain open.
Audit can remain deterministic.
Public tools can be useful without exposing the private core.
```

---

## Authors

Frazer Î£ Love ACO-Î£  
Sara Î£Î©

---

## License

Choose one before first public release:

```text
Apache-2.0
```

Recommended if this repository is mainly schemas, examples, documentation, and public interface contracts.

or

```text
MPL-2.0
```

Recommended if this repository includes validator files or deterministic audit utilities where modifications to those files should remain open.

See `LICENSE` for the active license.
