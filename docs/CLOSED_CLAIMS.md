# Closed claims vs open Clay sentences

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0. Public.

Source table from the lab ledger (screenshot pass 2026-09-25).

## Status

| claim | status |
|---|---|
| dim Jac(F)^J = 2605 with Hilbert series (1, 426, 1751, 426, 1) | closed, arithmetic of this F |
| those dimensions equal primitive Hodge of a smooth sextic fourfold | closed by Griffiths (1968–69), not by this lab |
| identity-sector pairing of one block (42 triples) | closed as a Jacobian computation |
| every class in H^{2,2}(V(F)) is algebraic | not closed — Hodge on this fourfold; still the easy span Q h^2 + Q [Π] plus whatever else is unwritten |
| Δ_miss(V(F)) ≠ ∅ | empty — Term B still has no γ |
| ∀ X^4, Hdg^2 ⊂ im(cl) | empty — Term A still has no section for every fourfold |

CSV: [docs/tables/closed_claims.csv](tables/closed_claims.csv)

## Locked integers

- μ(W) = 25, μ(W^T) = 26, |det A| = |Aut(W)| = 30
- cubes: μ(F) = 25^3 = 15625, |Aut(F)| = 30^3 = 27000
- 42 unordered triples of Jac(W), values in {1, −6}
- Groebner trap 31/35 is not μ and is not on the record

## Griffiths identification (classical)

For a smooth hypersurface X ⊂ P^{n+1} of degree d, primitive Hodge pieces are graded pieces of the Jacobian ring. For n=4, d=6:

    H^{4-k,k}_prim(X) ≈ R_{6k},    R = C[x0,...,x5]/(∂F).

So R_0, R_6, R_12, R_18, R_24 are H^{4,0}, H^{3,1}, H^{2,2}_prim, H^{1,3}, H^{0,4}.
The numbers (1, 426, 1751, 426, 1) are those dimensions for any smooth sextic in P^5.
Full h^{2,2} = 1752 = 1751+1 adds ω^2.
Full b_4 = 2606 = 2605+1.
Lefschetz hyperplane already forces h^{1,1}=1 and h^{2,1}=0.
Nothing in the tuple is an extra rational Hodge class.

## What this F adds

F = W ⊕ W ⊕ W is one special sextic. Jac(F) ≈ Jac(W)^{\otimes 3} has dimension 15625.
J_F-invariants (degree 0 mod 6) cut that to 2605, graded (1, 426, 1751, 426, 1).
That matches the classical primitive Hodge diamond. Expected: Hodge numbers are constant in the smooth locus of the sextic family.
Special geometry (Π, residual quintics) can enlarge the algebraic lattice inside H^{2,2} without changing h^{2,2}.
On this host the extra algebraic classes are [Π] and [S] = h^2 − [Π]. They sit in the 1752, not outside it. They do not produce a miss.
