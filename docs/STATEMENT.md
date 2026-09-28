<!--
Copyright (c) 2026 Benjamin Stanley Frohman. All rights reserved.
Released under Apache-2.0 license as described in the file LICENSE.
Author: Benjamin Stanley Frohman
-->

# The sentence

Author: Benjamin Stanley Frohman
Copyright (c) 2026 Benjamin Stanley Frohman
License: Apache-2.0

Let X be a smooth projective variety over a finite field F_q.
Fix a prime ell not equal to the characteristic. After the Tate twist (i),
the cycle class map lands in Galois invariants:

    cl : CH^i(X)_Q \otimes Q_ell  \to  H^{2i}_et(X_{bar F_q}, Q_ell(i))^{Gal}.

Tate conjecture (codimension i): that map is surjective.

For fourfolds and i = 2 the missing objects are surfaces over a finite
field whose classes span the Gal-fixed part of H^4_et(Q_ell(2)).

The numerical shadow: geometric Frobenius acts on H^{2i} with eigenvalue
q^i on those invariants. For i = 2 that is the root q^2 on H^4.
Weil already gives |alpha| = q^2 on H^4. The root is a condition on a
class, not a construction of a cycle.

Lean name of the same sentence:
https://github.com/BenFrohman/TateConjecture/blob/main/TateConjecture/Basic.lean
There is no term of that type in either repository.
