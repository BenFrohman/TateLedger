# TateLedger

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23652982.svg)](https://doi.org/10.5281/zenodo.23652982) [![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**Author:** Benjamin Stanley Frohman ([@BenFrohman](https://github.com/BenFrohman))
**Copyright:** Copyright (c) 2026 Benjamin Stanley Frohman
**License:** [Apache-2.0](LICENSE)

Public ledger of the Tate conjecture.

This repository is **not** a proof of Tate.
This repository is **not** a proof of Hodge.
It names the sentence, records implications, and points at prior theorems.

Lean skeleton of the same sentence: [BenFrohman/TateConjecture](https://github.com/BenFrohman/TateConjecture)
Complex Hodge ledger: [BenFrohman/HODGE](https://github.com/BenFrohman/HODGE)

## The sentence

Let `X` be smooth projective over a finite field `F_q`.
After a Tate twist, the cycle class map lands in Galois invariants:

    cl : CH^i(X)_Q \otimes Q_\ell  \to  H^{2i}_et(X_{bar F_q}, Q_\ell(i))^{Gal}

Tate: that map is surjective.

The numerical shadow is that geometric Frobenius on `H^{2i}` has eigenvalue `q^i` on the Tate classes. For fourfolds and `i = 2` that shadow is `q^2` on `H^4`. Weil already forces `|\alpha| = q^2` on `H^4`. The root `q^2` is a condition on a class, not a surface.

Writing `cl(z) = \gamma` is the hard arrow. This repository does not write those cycles for an unspecified `X`.

## Files

| File | Content |
|---|---|
| [docs/STATEMENT.md](docs/STATEMENT.md) | the sentence |
| [docs/IMPLICATIONS.md](docs/IMPLICATIONS.md) | motives, zeta poles, BSD, Brauer, standard conjectures |
| [docs/KNOWN_CASES.md](docs/KNOWN_CASES.md) | theorems in the literature |
| [docs/LITERATURE.md](docs/LITERATURE.md) | pointers to prior work |
| [docs/HODGE_COMPARISON.md](docs/HODGE_COMPARISON.md) | Hodge vs Tate |
| [docs/NOT_THIS_HOST.md](docs/NOT_THIS_HOST.md) | why V(F) over C does not set Tate up |
| [SECURITY.md](SECURITY.md) | integrity policy |
| [CONTRIBUTING.md](CONTRIBUTING.md) | patch rules |

## What this repo does not do

- Does not inhabit Tate with True.intro, an axiom-as-theorem, or sorry.
- Does not treat an eigenvalue `q^2` as a cycle.
- Does not treat a complex (2,2)-form as a Galois-fixed class.
- Does not import a Frohmanian curve as an algebraic cycle.
- Does not claim Hodge on V(F) discharges Tate, or conversely.

Tate stays open. Hodge stays open.

---
## Archival DOI & Cryptographic Provenance

- **Dedicated 1-to-1 Zenodo DOI:** [10.5281/zenodo.23652982](https://doi.org/10.5281/zenodo.23652982)
- **Author:** Benjamin Stanley Frohman (ORCID: [0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718))
- **License:** Apache License, Version 2.0 (`Copyright (c) 2026 Benjamin Stanley Frohman`)
- **Earliest Commit Provenance:** `50953973410714364f5815a21897dcb594b93bf6` (2026-09-28 05:16:55 AM CDT (UTC-5))
- **SealGuard SHA-256 Merkle Root:** `bede94079ac02b1b1cac9098e6becfd2b5ec8f43674c8cbfe9290a0b8b508db8` (`PROVENANCE_MERKLE_ROOT.json`)
- **Titan Audit Certificate:** `audit/TITAN_AUDIT_CERTIFICATE.json` (Ed25519 key `b428fb72676f1c52`)
- **Scope & Scientific Boundary:** Reference ledger cataloging literature results and open problems; explicitly does not claim a proof of the general Tate or Hodge conjectures.
