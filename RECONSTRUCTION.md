# Reconstruction: classical three-points, not a fake FJRW table

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.

What was asked: a table of genus-zero three-points of (F, ⟨J⟩), or a reconstruction of that ring.

What is written here: the **classical residue ring** of the atom and its Thom–Sebastiani cube. That is the B-model Jacobian. It is the input to a reconstruction theorem. It is not the output of Guéré, and it is not the twisted-sector FJRW CohFT of F.

## Atom W

    W = u^5 v + v^6
    Jac(W) basis: {u^i v^j : 0≤i≤3, 0≤j≤5} ∪ {u^4},   dim = 25
    LTs: v^6, u^5, u^4 v
    Reduction: v^6 = 0,   u^4 v = 0,   u^5 = -6 v^5
    Socle: u^3 v^5, degree 8
    Hilbert: 1,2,3,4,5,4,3,2,1

Residue three-point on W:

    ⟨a,b,c⟩_W  =  coefficient of u^3 v^5 in  a b c  after reduction.

Nonzero values are only 1 and -6. The -6 is u^8 = u^3 u^5 = -6 u^3 v^5.

Unordered triples with ⟨a,b,c⟩ ≠ 0: 42 of them. Table: docs/three_points_W.csv

Two-point pairing recovered as ⟨a,b,1⟩:

    (1, u^3 v^5) = 1
    (v^k, u^3 v^{5-k}) = 1
    (u v^k, u^2 v^{5-k}) = 1
    (u^4, u^4) = -6

## Cube F = W ⊕ W ⊕ W

    Jac(F) ≅ Jac(W) ⊗ Jac(W) ⊗ Jac(W),   dim 15625

Classical three-point on pure tensors:

    ⟨a1⊗a2⊗a3,  b1⊗b2⊗b3,  c1⊗c2⊗c3⟩_F
    =  ⟨a1,b1,c1⟩_W · ⟨a2,b2,c2⟩_W · ⟨a3,b3,c3⟩_W.

That is the reconstruction of the **identity-sector classical ring**. It multiplies because the Jacobian multiplies. It does not multiply virtual classes on spin moduli.

J = (ζ_6)^6 acts by degree: a tensor is invariant iff deg a1 + deg a2 + deg a3 ≡ 0 (mod 6).

    dim Jac(F)^{deg ∑ ≡ 0 mod 6} = 2605.

(The six residue classes of the 15625-dimensional space split as 2605 + 5×2604.)

Socle of F is (u^3 v^5)^{⊗ 3}, degree 24 ≡ 0 mod 6, invariant.

## What this is not

- Not FJRW twisted sectors. ⟨J⟩ has five non-identity elements. Those sectors are not Jac(F).
- Not Guéré Hodge integrals.
- Not a claim that 2605 equals b_4 or h^{2,2}. Very-general sextic has b_4=2606; this host is special.
- Not Term B.

A reconstruction theorem that identifies FJRW_0(F,⟨J⟩) with this Jacobian product would close the **classical identity-sector** ring. That theorem is not proved in this file. The table that tensors is the W-table below.
