# FJRW reconstruction theorems, applied to this atom

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.
Date: 25 September 2026

There is not one theorem. There are three different reconstructions. Mixing them is how a Jacobian pairing becomes a fake correlator table.

## 1. Krawitz (LG mirror, the ring itself)

Krawitz, arXiv:0906.0796. For an invertible quasihomogeneous W:

- State spaces: FJRW(W, G) is isomorphic, as a bigraded vector space, to the orbifold Milnor ring of (W^T, G^T).
- Frobenius algebras: when G = Aut(W) (maximal diagonal), G^T is trivial, so

      FJRW-ring(W, Aut)  cong  Jac(W^T)

as Frobenius algebras.

This atom is invertible of chain type. So

      FJRW(W, Aut(W))  cong  Jac(W^T)     dim 26
      FJRW(F, Aut(F))  cong  Jac(F^T)     dim 26^3 = 17576

if the theorem tensors under Thom-Sebastiani (Aut(F)=Aut(W)^3, F^T = W^T oplus W^T oplus W^T). That reconstructs the *maximal-group* A-model ring as a Jacobian. It does not reconstruct FJRW(F, <J>).

For G = <J>, the dual group G^T is not trivial. The B-model is an *orbifold* Jacobian, not Jac(F^T) raw. Chiodo-Ruan matches dimensions of FJRW(F,<J>) to Hodge of V(F) when the CY condition holds. That is a dimension match, not the 3-point tensor.

## 2. WDVV reconstruction (genus zero from 3-points)

Kontsevich-Manin, adapted to FJRW by Fan-Jarvis-Ruan and by Francis / Chen / Krawitz-Priddis.

The genus-zero primary potential is determined by the pairing and the 3-point constants

      eta(gamma1, gamma2 bullet gamma3) = <gamma1, gamma2, gamma3>_{0,3}

plus WDVV, string, and the degree axiom, *once those 3-points are known*, and if primitive degrees are small enough that higher-point basics reduce.

This theorem says: if you have the 3-point table, you get all genus-zero primaries. It does not produce the 3-point table.

For one block W, identity-sector 3-points are the residue pairing against u^3 v^5 (42 triples, four of them -6). Twisted-sector 3-points of (W, <J>) or of (F, <J>) are the missing input.

## 3. Teleman / Givental (higher genus from a semisimple Frobenius manifold)

If the CohFT is semisimple, the ancestor potential is reconstructed from the genus-zero Frobenius manifold. Francis-He-Shen treat semisimplicity of FJRW of invertible polynomials; this chain has gcd(p-1,q)=2 and is not ADE (inner modality 6). Semisimplicity of (W,G) is not a closed theorem in this lab.

Guere is not a reconstruction of the ring. It is a formula for lambda_g cup c_vir on *one chain*. It does not reconstruct F = W oplus W oplus W.

## What is reconstructed here vs what is not

| object | theorem | status |
|---|---|---|
| Jac(W) as Frobenius algebra | residue pairing | closed, 25, socle u^3 v^5 |
| Jac(F) identity sector | Thom-Sebastiani tensor of pairings | closed, product of block 3-points |
| dim Jac(F)^{<J>} | Hilbert, deg 0 mod 6 | closed, 2605 |
| FJRW(W, Aut) as algebra | Krawitz | isomorphic to Jac(W^T), dim 26 |
| FJRW(F, Aut) as algebra | Krawitz + TS | isomorphic to Jac(F^T), dim 17576 |
| FJRW(F, <J>) 3-point table | WDVV input | not computed |
| higher genus of F | Teleman | needs semisimplicity, open |
| a class in H^{2,2}(V(F)) missed by cl | none of the above | empty |
