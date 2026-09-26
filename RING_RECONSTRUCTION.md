# Reconstruction of the identity-sector ring, not a fake FJRW table

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.
Date: 25 September 2026

## What can be written now

The classical Frobenius algebra of the Thom-Sebastiani sum

    F = W oplus W oplus W,    W = u^5 v + v^6

is the tensor cube of Jac(W). On that algebra, genus-zero three-points in the identity sector factor:

    <a1 otimes a2 otimes a3,  b1 otimes b2 otimes b3,  c1 otimes c2 otimes c3>_F
    =  product_{k=1..3}  <ak, bk, ck>_W.

Each block three-point is the residue pairing against the socle u^3 v^5:

    <a,b,c>_W  =  (a b c,  u^3 v^5).

From the locked pairing table (docs in SingularityLab):

    (1, u^3 v^5) = 1
    (v^k, u^3 v^{5-k}) = 1    for k = 0..5
    (u v^k, u^2 v^{5-k}) = 1  for k = 0..5
    (u^4, u^4) = -6

The -6 is u^5 = -6 v^5 twice: u^8 = u^3 u^5 = -6 u^3 v^5.

That product formula is a theorem about Jacobian algebras. It is not a theorem about the virtual class on F-spin moduli.

## J-invariants, computed

Weights (1,1), basis degrees of Jac(W):

    deg: 0 1 2 3 4 5 6 7 8
    #  : 1 2 3 4 5 4 3 2 1     (sum 25)

J scales every variable by exp(2 pi i / 6). A tensor monomial is invariant iff total degree is 0 mod 6.

    dim Jac(F)^{<J>} = 2605.
    dim Jac(F)       = 15625 = 2605 + 5*2604.

2605 is the same integer as primitive middle Betti of a general sextic fourfold in P^5 (b_4 - 1 = 2606 - 1). V(F) is special (contains a plane), so this is a numerical coincidence to check, not a Hodge miss.

## Krawitz arrow (G_max, not <J>)

Krawitz: FJRW ring of (W, Aut) is isomorphic, as a Frobenius algebra, to the Milnor ring of W^T.
For the sum: Aut(F) = Aut(W)^3, F^T = W^T oplus W^T oplus W^T,

    FJRW(F, Aut(F))  cong  Jac(F^T)    (dim 26^3 = 17576)

as algebras, if the invertible-potential theorem applies to each block and tensors. That reconstructs the maximal-group A-model as the dual Jacobian. It does not list the twisted-sector three-points of the smaller group <J>.

## What remains open for (F, <J>)

<J> has six sectors. Identity is the Jacobian piece above. J^k for k=1..5 are narrow (Fix=0). Three-points that mix those sectors live on F-spin moduli and do not factor as a product of three W-correlators.

A closing table would name every nonzero

    <alpha, beta, gamma>_{0,3}^{F, <J>}

including mixed-sector insertions. This lab has the identity-sector B-model constants. It does not have that table.

Not Term B. Not a class in H^{2,2}(V(F)).
