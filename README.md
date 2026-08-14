# The Quadratic Cost of Replicable Distribution Estimation

## Abstract

Estimating a distribution on $k$ symbols to expected total-variation error $\alpha$ needs $\Theta(k/\alpha^2)$ samples.
Under algorithmic replicability, the best known upper bound is $O(k^2\log(1/\rho)/(\alpha^2\rho^2))$.
Whether the quadratic alphabet dependence is necessary was left open by Bun et al.
We prove that it is.
Every $\rho$-replicable estimator with expected error at most $\alpha$ requires

$$\Omega\\\\\\!\left(\frac{k^2}{\alpha^2\rho^2}\right)$$

samples, for all sufficiently small universal $\alpha$ and $\rho$.
The lower bound holds for arbitrary randomized estimators and matches every polynomial dependence in the known upper bound.
Our proof introduces an average-distortion partition principle.
Fixing the public randomness turns a replicable estimator into canonical output cells.
Expected accuracy does not bound every cell, so bounded-diameter partition arguments do not apply.
Instead, we show that cells with low average distortion cover constant measure, that each such cell has exponentially small measure, and that Gaussian-profile isoperimetry forces total boundary $\Omega(\sqrt{k})$.
The hard instances form a smooth toroidal family of categorical distributions.
Nearby parameters generate statistically indistinguishable samples at scale $\sqrt{k}/(\alpha\sqrt m)$.
Thickening all canonical cells to this scale converts their boundary into nonreplicability, yielding the result by coarea.

## Keywords

quadratic, cost, replicable, distribution, estimation, estimating, symbols, expected, total-variation

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
