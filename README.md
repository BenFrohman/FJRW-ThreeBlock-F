# FJRW of the three-block sum F

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23652984.svg)](https://doi.org/10.5281/zenodo.23652984) [![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0. Public.

This repo states one problem. It does not solve it.

Atom lab: [BenFrohman/SingularityLab](https://github.com/BenFrohman/SingularityLab)

## The atom

    W = u^5 v + v^6 = X^5 Y + Y^6
    μ(W) = 25,   |Aut(W)| = 30,   ĉ = 4/3

Guéré's chain formula applies to this W. Fan–Shen labels (p,q)=(5,6), gcd(4,6)=2.

## The sum that is not a product

    F = W(x0,x3) + W(x1,x4) + W(x2,x5)  ⊂ P^5
    Jac(F) ≅ Jac(W)^{⊗ 3}     dim 15625
    Aut(F) ≅ Aut(W)^3          order 27000
    ĉ(F) = 4

State spaces tensor. Correlators do not.

See [PROBLEM.md](PROBLEM.md).

No Guéré table is claimed. No Hodge miss. Not Term B.

---
## Archival DOI & Cryptographic Provenance

- **Dedicated 1-to-1 Zenodo DOI:** [10.5281/zenodo.23652984](https://doi.org/10.5281/zenodo.23652984)
- **Author:** Benjamin Stanley Frohman (ORCID: [0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718))
- **License:** Apache License, Version 2.0 (`Copyright (c) 2026 Benjamin Stanley Frohman`)
- **Earliest Commit Provenance:** `515ac1028fa0c5a4f678e7b47221c7d7244fbbd9` (2026-09-25 03:31:31 PM CDT (UTC-5))
- **SealGuard SHA-256 Merkle Root:** `177e4a6e1aec90be87de21d0c4e87d630bc0d8aa09930b8062dc2d0866ec218b` (`PROVENANCE_MERKLE_ROOT.json`)
- **Titan Audit Certificate:** `audit/TITAN_AUDIT_CERTIFICATE.json` (Ed25519 key `b428fb72676f1c52`)
- **Scope & Scientific Boundary:** Defines the three-block FJRW problem and explicitly tabulates the correlators that lie beyond pure concavity axioms; does not claim an unproved closed-form evaluation of open mixed correlators.
