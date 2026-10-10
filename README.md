# Fractional De Giorgi Conjecture in Dimension Four

This repository contains two AI-assisted research manuscripts on one-dimensional symmetry for the fractional Allen–Cahn equation in dimension four, covering the ranges $0<s<1/2$ and $1/2<s<1$.

**Draft status:** Both manuscripts present candidate proofs and state that the team is continuing to verify all proofs. The summaries below describe the statements and arguments in the current drafts.

## Manuscripts

### 1. Stable nonlocal cones and the fractional De Giorgi conjecture in dimension four below one half

[Read the PDF](fractional_degiorgi_N4_less-half.pdf)

- **Range:** $0<s<1/2$
- **Manuscript date:** October 7, 2026
- **Length:** 57 pages
- **Candidate-proof date stated in the draft:** October 2, 2026

The manuscript states one-dimensional symmetry for bounded entire classical solutions in $\mathbb{R}^4$ that are strictly increasing in one coordinate, without prescribed directional limits (Theorem 1.2).

Its geometric statement classifies nontrivial stationary stable nonlocal perimeter cones in $\mathbb{R}^3$ as halfspaces for every perimeter order $0<p<1$, where $p=2s$. The hypotheses include a locally one-sided smooth boundary away from the origin, a compact smooth spherical link, and stability under compact variations away from the origin; no connectedness of the link is assumed (Theorem 1.3).

The argument develops angular-kernel estimates and normal-flux pinching, then connects the cone classification to the fractional Allen–Cahn equation.

### 2. The fractional De Giorgi conjecture in dimension four for 1/2 < s < 1

[Read the PDF](fractional_degiorgi_N4_bigger-half.pdf)

- **Range:** $1/2<s<1$
- **Manuscript date:** October 7, 2026
- **Length:** 124 pages
- **Candidate-proof date stated in the draft:** September 19, 2026

The manuscript states one-dimensional symmetry for bounded entire classical solutions in $\mathbb{R}^4$ that are strictly increasing in one coordinate, without prescribed directional limits (Theorem 1.1).

The argument first addresses the classification of bounded stable entire classical solutions in $\mathbb{R}^3$ as constant wells or planar layers (Theorem 1.2). Its main ingredients include transition-sheet separation, profile and curvature estimates, a tangential trace operator, surface stability, and a capacity argument. The four-dimensional conclusion then uses directional limits, global minimality, and minimizer rigidity.

## Common equation and conclusion

Both manuscripts consider

$$
(-\Delta)^s u = u-u^3 \quad \text{in } \mathbb{R}^4,
\qquad \partial_{x_4}u>0,
$$

with $u$ bounded and classical, and with the Fourier normalization $|\xi|^{2s}$ for the fractional Laplacian. Neither manuscript assumes limits as $x_4\to\pm\infty$.

The stated conclusion is

$$
u(x)=q_s(e\cdot x-a),
\qquad e\in\mathbb{S}^3,\quad e_4>0,\quad a\in\mathbb{R},
$$

where $q_s$ is the increasing one-dimensional layer, normalized by $q_s(0)=0$ and $q_s(t)\to\pm1$ as $t\to\pm\infty$.

The two manuscripts address the open intervals on either side of $s=1/2$; they do not include the case $s=1/2$ in their main statements.

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF. Include the [repository URL](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture) and the commit hash or a commit-specific PDF link for the version consulted, so that the cited draft can be identified after revisions.

## Keywords

Fractional De Giorgi conjecture; fractional Allen–Cahn equation; one-dimensional symmetry; monotone solutions; stable solutions; nonlocal minimal cones; spherical links; curvature estimates; layer separation.
