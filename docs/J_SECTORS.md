# (F, ⟨J⟩) genus-zero three-points — what is computed

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0. Public.
Date: 25 September 2026

This file is the grind of the ⟨J⟩ table. It does not invent mixed-sector virtual-class numbers.

F = W ⊕ W ⊕ W, W = u^5 v + v^6, deg F = 6, weights (1,1,1,1,1,1),
J_F = (ζ_6,ζ_6,ζ_6,ζ_6,ζ_6,ζ_6), ⟨J⟩ of order 6, ĉ = 4.

## 1. Sectors (closed)

J^k scales every coordinate by ζ_6^k. Fix(J^k) = {0} unless 6 | k.

| g | Fix | type | dim H_g | age(g) |
|---|---|---|---|---|
| 1 | ℂ^6 | broad | 2605 = dim Jac(F)^⟨J⟩ | 0 |
| J | {0} | narrow | 1 | 1 |
| J^2 | {0} | narrow | 1 | 2 |
| J^3 | {0} | narrow | 1 | 3 |
| J^4 | {0} | narrow | 1 | 4 |
| J^5 | {0} | narrow | 1 | 5 |

Total 2605 + 5 = 2610. That is dim H^*(V(F)): b_0+b_2+b_4+b_6+b_8 = 1+1+2606+1+1 = 2610.

The identity of the FJRW ring is the J-sector vacuum e_1 = 1_J, not a vector in Jac(F).
The five narrow states are, under Chiodo–Ruan, the Lefschetz line

    e_k  ↔  ω^{k-1} ∈ H^{2k-2}(V(F)),    k = 1,…,5.

They are algebraic. They are not a miss class.

## 2. Selection (closed)

A primary three-point ⟨α_g, β_h, γ_k⟩_{0,3} can be nonzero only if

    g h k = J    in ⟨J⟩

(the usual FJRW decoration at genus 0 with three markings) and the degree axiom holds.
Writing sectors as J^a, J^b, J^c with a,b,c ∈ {0,1,2,3,4,5}:

    a + b + c ≡ 1  (mod 6).

## 3. What the axioms fix among narrow states

String / pairing: ⟨α, β, 1_J⟩_{0,3} = ⟨α, β⟩.
Dual narrow sectors are (J^k, J^{6-k}) for k=1,2,3.

Poincaré pairing on V(F) ⊂ ℝ^5:

    ∫_X ω^4 = deg(X) = 6.

So geometrically

    ⟨ω^i, ω^{4-i}⟩ = 6,    i = 0,1,2.

FJRW may rescale the five vacuums; the pairing of dual narrow sectors is nonzero by axiom. The integer 6 is the geometric pairing, not a virtual-class computation on F-spin moduli.

Allowed narrow triples by a+b+c ≡ 1 mod 6, with a,b,c ∈ {1,2,3,4,5}:

    (1,1,5), (1,2,4), (1,3,3), (2,2,3)

and permutations. The first three are pairing/string against 1_J.
(2,2,3) is ⟨ω, ω, ω^2⟩, geometrically ∫ ω^4 = 6.

No other narrow-only triple survives the selection rule.

## 4. Identity-sector (broad) three-points — closed as Jacobian data

The g=1 sector is Jac(F)^⟨J⟩, Hilbert (1, 426, 1751, 426, 1) in degrees 0,6,12,18,24.
On pure tensors the residue three-point factors

    ⟨a1⊗a2⊗a3, b1⊗b2⊗b3, c1⊗c2⊗c3⟩_F
    = ∏_{k=1}^3 ⟨a_k, b_k, c_k⟩_W

with each block number from the 42 triples (values in {1, −6}).
That is Jac(F), not the virtual class of an F-spin curve.
CSV of the atom: docs/three_points_W.csv

## 5. Mixed broad–narrow three-points — OPEN

Any triple that inserts at least one class from Jac(F)^⟨J⟩ and at least one e_k, k≥1, with a+b+c ≡ 1 mod 6, is an integral on F-spin moduli.
Guéré does not evaluate it (one chain).
Krawitz does not evaluate it (G_max).
The 42 triples do not multiply to it.

Those entries stay unmarked. Filling them with 0, 1, or 6 without the virtual class is a fake result.

## 6. What this does not close

- Term B. The five narrow states are ω^{k-1}, algebraic.
- Term A. A 3-point table is not a CycleSection for every fourfold.
- FJRW(F, Aut(F)). That is Problem Aut, dim 17576, Jac(F^T).
