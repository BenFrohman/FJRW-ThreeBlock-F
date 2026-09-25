# Problem. FJRW(F) is not a product of three FJRW(W)

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.

Two statements. Both true. Not the same statement.

## 1. Guéré applies to the atom, not to F

A chain is one path of variables

    W_chain = x1^{a1} x2 + ··· + x_{N-1}^{a_{N-1}} x_N + x_N^{a_N}.

Guéré, Hodge integrals in FJRW theory (Michigan Math. J. 66, 2017; arXiv:1509.07047), Theorem 0.1: for any chain, any admissible G, any genus,

    λ_g^vee · c_vir^{PV}(γ_1,…,γ_n)
    = lim_{t→1} (∏_{j=1}^N c_{t_j}(-R^• π_* L_j)) · c_{t_{N+1}}(E^vee)

with t_{j+1} = t_j^{-a_j} and r_j = #{i : γ_j(i)=1} counting broad markings.

Our atom is N=2, a1=5, a2=6:

    W = u^5 v + v^6.

W-spin relations:

    L_u^{⊗ 5} ⊗ L_v ≃ ω_log,    L_v^{⊗ 6} ≃ ω_log.

G may be Aut(W) of order 30 or ⟨J⟩ of order 6. The formula applies to (W,G) and separately to (W^T, G).

It does not evaluate the integrals. A run is not on disk.

## 2. Three-block F does not factor as a product of correlators

    F = W(x0,x3) + W(x1,x4) + W(x2,x5).

Thom–Sebastiani: disjoint variables, sum of potentials.

What factors:

    Jac(F) ≅ Jac(W) ⊗ Jac(W) ⊗ Jac(W),    dim = 25^3 = 15625
    Aut(F) ≅ Aut(W)^3,                    |Aut(F)| = 30^3 = 27000
    ĉ(F) = 4/3 + 4/3 + 4/3 = 4

What does not factor: an FJRW correlator of F is an integral on one stack

    Mbar_{g,n}^{F, G_F}

of F-spin orbicurves. An F-spin structure is six line bundles L_0,…,L_5 tied by all three monomial relations at once. That stack is not

    Mbar_{g,n}^{W,G} × Mbar_{g,n}^{W,G} × Mbar_{g,n}^{W,G}.

A point of the product is three curves. A point of F-spin moduli is one curve carrying six roots of ω_log.

So even with every correlator of (W,G),

    ⟨α ⊗ β ⊗ γ⟩_{g,n}^{F}
    ≠
    ⟨α⟩_{g,n}^{W} · ⟨β⟩_{g,n}^{W} · ⟨γ⟩_{g,n}^{W}

in general. Mixed-block insertions have no such factorisation at all.

F is three disjoint paths. It is not the length-6 chain x0^a x1 + x1^b x2 + ··· + x5^c. Guéré applies to each block. It does not, as stated, apply to F.

## 3. Ledger

| object | factors? | status |
|---|---|---|
| Jac(F) | yes, Jac(W)^{⊗ 3} | closed, dim 15625 |
| Aut(F) | yes, product of groups | closed, order 27000 |
| ĉ(F) | yes, sum of charges | closed, ĉ=4 |
| genus-0 ring of one block | Fan–Shen, gcd=2 | dimensions 25/26, not structure constants |
| Hodge integrals of one block | Guéré applies | formula yes, numbers not run |
| correlators of F | not a product of block correlators | open |
| a class in H^{2,2}(V(F)) | no | not produced |

The honest sentence: Guéré gives a computable class on the spin moduli of this atom. Three copies of that atom define the sextic fourfold, and their Jacobians tensor. Their enumerative theories do not multiply. That is why a three-block FJRW potential of F is a separate problem.
