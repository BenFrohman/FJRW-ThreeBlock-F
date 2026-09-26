# Two groups, two problems

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.

## Group 1.  ⟨J⟩  (order 6)

J_F = (ζ_6,ζ_6,ζ_6,ζ_6,ζ_6,ζ_6).

State space of FJRW(F, ⟨J⟩):

- identity sector: Jac(F)^{deg-sum ≡ 0 mod 6}, dim 2605
- five narrow sectors J^r, r=1..5: no fixed coordinates, dim 1 each
- total dim 2605 + 5 = 2610

2610 is also ∑ b_i of a smooth sextic fourfold in P^5
(1 + 1 + 2606 + 1 + 1). That is the Chiodo–Ruan dimension count, not a product table.

The **full FJRW table** of (F, ⟨J⟩) is every genus-zero three-point

    ⟨α, β, γ⟩_{0,3}^{F, ⟨J⟩}

with α,β,γ running over a basis of those 2610 states.

What is closed:
- identity-sector three-points on pure tensors factor as ∏_k ⟨a_k,b_k,c_k⟩_W
- the W-table is 42 unordered triples, values in {1, −6}
- pairing of dual narrow sectors J^r with J^{6-r} is 1 up to the standard FJRW pairing axiom (not recomputed here)

What is open:
- mixed-sector three-points (two identity states and one narrow, or three narrows with r+s+t ≡ 0 mod 6, or one identity and two narrows)
- those live on F-spin moduli and do not factor as three W-correlators

That open list **is** the full table of (F, ⟨J⟩). It is not on disk.

## Group 2.  Aut(F)  (order 27000)

Krawitz: FJRW(W, Aut(W)) ≅ Jac(W^T) as Frobenius algebras, dim 26.
If Thom–Sebastiani tensors at G_max,

    FJRW(F, Aut(F))  ≅  Jac(F^T),   dim 26^3 = 17576.

Different state space, different ring, different table. Fan–Shen supplies the two-variable block when G = G_max, including the non-coprime case gcd(4,6)=2.

## Not the same problem

| | (F, ⟨J⟩) | (F, Aut(F)) |
|---|---|---|
| |G| | 6 | 27000 |
| state-space dim | 2610 | 17576 |
| reconstruction | Chiodo–Ruan dimensions vs Hodge of V(F) | Krawitz ≅ Jac(F^T) |
| identity 3-points | tensor of W-table | not the same |
| mixed / twisted 3-points | open | different open |
| Term B | empty | empty |
