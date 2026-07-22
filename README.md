This repository contains the source of the **O6** Cosmochrony paper  
*Matrix-Level Dynamic Redundancy and the Structural Confinement of the Cascade Exponent β*.

**Version 1.1.1.** The LPS results and fixed-representation obstruction are unchanged.
This version scopes the exponent equation to the growing-degree LPS closure and its
multiplicative productive-frontier model. It does not transfer that equation to the
fixed-degree Heisenberg Cayley cascade.

This work extends the **spectral relaxation programme** by investigating the
next structural layer left open by O5: whether the small phenomenological value
of the cascade exponent

$\beta^\* \in (0.09, 0.13)$

can arise from a matrix-level admissible redundancy mechanism.

While **O5** proves that vertex-based admissible frontiers and fixed-dimensional
representation-theoretic mechanisms cannot explain the smallness of $\beta$,
it identifies matrix-level dynamic redundancy as a class of candidate
mechanisms. The present work performs the first explicit construction and test
at this level.

The central object introduced here is the **Steinberg-matrix fingerprint**

$\pi_{\mathrm{mat}}(v) = \mathrm{vec}\!\left(P_v - \frac{1}{q+1}J\right)$,

where $P_v$ is the permutation matrix of the Möbius action of
$v \in PSL(2,\mathbb{F}_q)$ on $\mathbb{P}^1(\mathbb{F}_q)$.

# Core Result

The paper establishes a **representation-theoretic obstruction** to extracting the
cascade exponent from any fixed finite-dimensional fingerprint.

Starting from:

- the matrix-level admissible frontier
- the redundancy functional
  $R_n = |\partial^{B,\mathrm{mat}} S_n| / |\partial S_n|$
- numerical experiments on LPS families $X_{5,q}$ for $q \in \{29,41,61\}$

the analysis shows that:

- the Steinberg-matrix fingerprint achieves a first **q-structural saturation**
- the ratio $|S^\*|/|G|$ decreases as $q$ grows
- but the saturation depth remains **bounded**, occurring at BFS depth 6 for all tested $q$

As a consequence, the pre-saturation window is too short to support any genuine
power-law regime of the form

$R_n \sim p(n)^{-\alpha}$,

and therefore too short to extract a stable effective exponent $\beta_{\mathrm{eff}}$.

# Structural Role of O6

O6 does not derive the phenomenological value of $\beta$.

Instead, it proves that an entire class of candidate mechanisms is structurally
insufficient:

- **O3** identified the phenomenological window for $\beta$
- **O5** showed that vertex-based and low-level representation-theoretic mechanisms fail
- **O6** proves that **no fixed finite-dimensional representation** can produce the
  required scaling on the LPS cascade studied here

The cascade exponent is therefore no longer attributable to any static finite-dimensional
encoding of admissible transitions within the LPS cascade studied here.

The conditional formula $\beta_{\mathrm{eff}}=1/(1/2+\alpha)$ belongs to that LPS model:
the $1/2$ term comes from the expander-side growth equation, and the insertion of the
redundancy functional as a multiplicative productive fraction is an explicit modelling
assumption. O6 supplies no native Heisenberg growth carrier, so the formula cannot be
transferred verbatim to the fixed-degree nilpotent cascade.

# What O6 Adds

O6 introduces a decisive new structural result:

- the first explicit **matrix-level** admissible fingerprint
- the first explicit **q-structural saturation** at ambient dimension $O(q^2)$
- a proof that bounded-depth saturation is universal for all fixed finite-dimensional
  representations
- a clear separation between **representation-theoretic saturation** and
  **genuinely dynamical saturation**

This turns the search for $\beta$ into a much sharper problem.

# Interpretation of the Obstruction

The obstruction established in O6 has a clear physical and structural meaning in the
Cosmochrony framework.

It shows that the smallness of $\beta$ cannot come from:

- the size of a fixed representation space
- the use of more refined but still finite-dimensional fingerprints
- the spectral richness of a larger graph alone

What matters is not merely dimension, but **depth**.

A fixed finite-dimensional encoding can only explore a bounded number of genuinely
independent admissible directions before saturating. Hence it cannot sustain the
long pre-saturation regime required for a power-law decay of the productive frontier.

In this sense, the cascade exponent $\beta$ is not a static representation-theoretic
quantity, but a genuinely dynamical one associated with a growing effective state space.

# Relation to Previous Steps

O6 preserves all previous structural results:

- spectral admissibility from **Step 1**
- binary-polyhedral maximality from **Step 2**
- three-level ADE stratigraphy from **Step 3**
- projective dynamics and support contraction from **O1**
- hierarchical amplification via growing valence from **O3**
- structural bound on valence growth from **O5**

It does not modify the mass formula itself.
Instead, it proves that the remaining small parameter $\beta$ cannot be generated within
any fixed finite-dimensional matrix framework on the LPS construction considered here.

# Conceptual Structure

O6 completes the next stage of the structural chain:

1. Spectral admissibility → mode selection
2. Spectral capacity → binary-polyhedral maximality
3. Spectral stratigraphy → discrete ADE levels
4. O1 → ordering via support contraction
5. O3 → amplification via valence growth
6. O5 → admissible frontier saturation and localisation of the problem
7. O6 → no-go theorem for fixed finite-dimensional fingerprints

The programme now excludes not only super-quadratic growth laws, but also the full class
of finite-dimensional static encodings as possible origins of the small cascade exponent.

# What O6 Resolves

O6 provides:

- a first explicit matrix-level admissible fingerprint at ambient dimension $O(q^2)$
- a proof of q-structural saturation for that fingerprint
- a universal bounded-depth saturation result for all fixed finite-dimensional
  representation-based fingerprints
- a no-go theorem excluding fixed finite-dimensional mechanisms as explanations of
  the proposed LPS cascade scaling
- a precise structural localisation of the remaining open problem

It shows that the hierarchy mechanism requires more than refined representation theory:
it requires a genuinely growing dynamical space of admissible directions.

# Residual Open Problem

Within the LPS construction, what remains open is how a **growing** admissible state
space could produce the required power-law redundancy decay. A separate model would
still be required to identify such an equation with growth on the Heisenberg substrate.

O6 therefore isolates the next necessary construction:

a **multi-step path fingerprint**

$\pi_k(v) = Ad(u)\otimes Ad(s_1)\otimes \cdots \otimes Ad(s_{k-1})$

living in a space of dimension $O(q^{2k})$.

Such a construction is expected to allow a pre-saturation window that grows with $q$,
which is precisely what is missing at the Steinberg-matrix level.

# Open Directions

1. **Multi-step path fingerprints**  
   Construct fingerprints in ambient dimension $O(q^{2k})$ for $k \ge 2$,
   with a pre-saturation window growing as a power of $q$

2. **Derivation of a genuine power-law regime**  
   Establish a regime where the redundancy functional satisfies

   $R_n \sim p(n)^{-\alpha}$

   over a sufficiently long interval to extract $\beta_{\mathrm{eff}}$

3. **Analytic bound on the bounded saturation depth**  
   Turn the observed depth-6 Steinberg saturation into a theorem

4. **Extension to other LPS primes and generators**  
   Test the robustness of the obstruction beyond the $p=5$ family

5. **Extension to quark and neutrino sectors**  
   Determine whether the same dynamical redundancy logic constrains the full flavour hierarchy

# Status

This framework is now:

- spectrally complete at the $O(q^2)$ matrix level
- structurally constrained beyond vertex-based descriptions
- free of fixed-dimensional representation-theoretic explanations for $\beta$ within the LPS model
- sharply focused on genuinely dynamical redundancy mechanisms

It does not assume:

- arbitrary matrix fingerprints
- unrestricted finite-dimensional encodings
- phenomenological tuning of redundancy exponents

# Repository Structure
```
paper/
├── out/ # Compiled O6 PDF
├── tex/ # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau, Matrix-Level Dynamic Redundancy and the Structural Confinement of the Cascade Exponent β, Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, and editorial refinement
benefited from iterative interactions with large language models used as
analytical assistants.
All theoretical results and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and alternative constructions
of matrix-level admissible redundancy mechanisms are welcome.

Please open an issue to discuss conceptual points,
technical details, or possible extensions.
