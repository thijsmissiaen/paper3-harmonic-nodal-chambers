# Harmonic Nodal Geometry, Zero-Curve Curvature, and the Transverse Integral Identity for Riemann's $\Xi$-Function

**DOI (Zenodo / CERN):** [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23641701.svg)](https://doi.org/10.5281/zenodo.23641701) [`10.5281/zenodo.23641701`](https://doi.org/10.5281/zenodo.23641701)  
**Author:** Thijs Missiaen (Independent Researcher, Belgium; ORCID: [0009-0007-3678-0810](https://orcid.org/0009-0007-3678-0810))  
**Repository & Version:** [`https://github.com/thijsmissiaen/paper3-harmonic-nodal-chambers`](https://github.com/thijsmissiaen/paper3-harmonic-nodal-chambers) (v1.1.0)  
**Manuscript:** [`paper/paper3_harmonic_nodal_chambers.pdf`](paper/paper3_harmonic_nodal_chambers.pdf) (15 pages, AMS-LaTeX / pdfTeX)  
**MSC 2020:** Primary 11M06, 30C15; Secondary 30D15, 31A05, 65G30  
**License:** MIT

> [!IMPORTANT]
> **Mathematical Scope & Prior-Art Context:** Any entire function $f(t-\mathrm{i}d) = R_f(d,t) + \mathrm{i}I_f(d,t)$ real on $\mathbb{R}$ (including Davenport–Heilbronn counterexamples) satisfies $\Delta R_f = \Delta I_f = 0$, the Cauchy–Riemann arc-length equation $\frac{\mathrm{d}\lvert R_f\rvert}{\mathrm{d}s} = \pm\lvert\nabla I_f\rvert = \pm\lvert f'(t-\mathrm{i}d)\rvert$ along smooth curves $\lbrace I_f = 0\rbrace$, and the transverse integral identity $\lvert f(t-\mathrm{i}d)\rvert^2 = \lvert f(t)\rvert^2 + 2\int_0^d u\,\widetilde{W}_f(u,t)\,\mathrm{d}u$. Assuming globally that $\Xi'(t-\mathrm{i}d) \neq 0$ in $d > 0$ is equivalent to the Riemann Hypothesis (Lagarias, 1999), while the vertex curvature $\kappa(\gamma_k) = \Xi''(\gamma_k)/\Xi'(\gamma_k)$ matches the de Bruijn–Newman zero-velocity ratio of Csordas, Smith, and Varga (1994), and the global nodal geometry builds on Speiser (1934) and Arias de Reyna (2003).

## Abstract

For any entire function $f(t-\mathrm{i}d) = R(d,t) + \mathrm{i}I(d,t)$ real on $\mathbb{R}$, Cauchy–Riemann orthogonality gives $\frac{\mathrm{d}\lvert R\rvert}{\mathrm{d}s} = \pm\lvert\nabla I\rvert = \pm\lvert f'(t-\mathrm{i}d)\rvert$ along smooth imaginary nodal curves $\lbrace I(d,t) = 0\rbrace$ away from critical points $f'(z) = 0$, while $\lvert f(t-\mathrm{i}d)\rvert^2 = \lvert f(t)\rvert^2 + 2\int_0^d u\,\widetilde{W}_f(u,t)\,\mathrm{d}u$ holds identically. Specializing to Riemann's $\Xi(t-\mathrm{i}d) = \xi(\frac{1}{2}+d+\mathrm{i}t)$, we clarify that global nodal monotonicity requires both critical-line Laguerre positivity $L_1(\Xi;\tau_k) > 0$ and the critical-point-free hypothesis $\Xi'(z) \neq 0$ in $d > 0$ (equivalent to the Riemann Hypothesis by Lagarias, 1999). Each real zero curve $R(d,t) = 0$ departs orthogonally from a simple zero $\gamma_k$ with vertex curvature $\kappa(\gamma_k) = \Xi''(\gamma_k)/\Xi'(\gamma_k)$, matching the de Bruijn–Newman zero-velocity ratio of Csordas, Smith, and Varga (1994). Under the canonical normalization $W(d,t) = 16\int_0^\infty y\sinh(2d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y$, transverse integration maps $\mathrm{sinc} _ {\mathrm{hyp}}(2u y)$ to $\mathrm{sinc} _ {\mathrm{hyp}}^2(d y)$ with filter ratio $\frac{\tanh(d y)}{d y} \in (0,1)$, verified alongside explicit counterexample mechanisms across $\gamma_1,\dots,\gamma _ {15}$ and $\Omega_1,\dots,\Omega _ {25}$.

## Main Analytical Results

1. **Universal Harmonic Structure, Off-Critical Dichotomy, and Euler–Stirling Boundary in $\sigma > 1$ (Propositions 2.1, 2.2, and 3.2; Theorem 3.1):** On $d = 0$, $I_f(0,t) \equiv 0$ and $\partial_d R_f(0,t) \equiv 0$. Transverse nodal curves $\Gamma \subset \lbrace I_f(d,t) = 0, d > 0\rbrace$ meet $d = 0$ exclusively at real critical points $f'(\tau) = 0$ with curvature $\kappa _ \Gamma(\tau) = \frac{f'''(\tau)}{3f''(\tau)}$. Along any critical-point-free arc of $\Gamma$ departing from $(0,\tau)$,

$$\frac{\mathrm{d}}{\mathrm{d}s}\lvert R_f(d(s), t(s))\rvert = \mathrm{sgn}\big(L_1(f;\tau)\big)\,\lvert\nabla I_f(d(s), t(s))\rvert = \mathrm{sgn}\big(L_1(f;\tau)\big)\,\lvert f'(t(s) - \mathrm{i}d(s))\rvert,$$

so an off-critical zero $(d _ {\star}, t _ {\star})$ ($d _ {\star} > 0$) requires either a boundary Laguerre failure $L_1(f;\tau) \le 0$ on $d = 0$ or an interior critical point $f'(z _ {\mathrm{crit}}) = 0$ in $d > 0$. In the Euler-product half-plane $d > \frac{1}{2}$ ($\sigma > 1$, outside the critical strip), $\partial_t\arg\Xi(t-\mathrm{i}d) > 0$ holds unconditionally for $d > d _ {\mathrm{Euler}}(t) > \frac{1}{2}$.

2. **Zero-Curve Curvature Jet and Csordas–Smith–Varga Velocity (Theorem 3.4):** Around each simple real zero $\gamma_k$, the real nodal curve $\mathcal{R} _ k := \lbrace (d, t _ {\mathcal{R} _ k}(d)) : R_f(d,t) = 0\rbrace$ departs orthogonally from $d = 0$ with Taylor expansion

$$t _ {\mathcal{R} _ k}(d) - \gamma_k = c _ {\mathrm{par}}(\gamma_k) d^2 + c _ {\mathrm{quart}}(\gamma_k) d^4 + \mathcal{O}(d^6), \qquad \kappa(\gamma_k) = \frac{f''(\gamma_k)}{f'(\gamma_k)}, \qquad c _ {\mathrm{par}}(\gamma_k) = \frac{f''(\gamma_k)}{2 f'(\gamma_k)}.$$

3. **Transverse Integral Identity, Conditional Rolle Turning Point, and Hyperbolic Low-Pass Ratio (Theorems 4.1 and 4.2):** Under canonical normalization $W(d,t) = 16\int_0^\infty y\sinh(2d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y$ and $\widetilde{W}(d,t) = W(d,t)/d = 32\int_0^\infty y^2\,\mathrm{sinc} _ {\mathrm{hyp}}(2d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y$, integrating $\partial_u\lvert\Xi(t-\mathrm{i}u)\rvert^2 = 2u \widetilde{W}(u,t)$ over $u \in [0,d]$ yields

$$\lvert\Xi(t - \mathrm{i}d)\rvert^2 = \lvert\Xi(t)\rvert^2 + 2\int_0^d u \widetilde{W}(u,t) \mathrm{d}u = \Big[\Xi(t)^2 + d^2\big(\Xi'(t)\big)^2\Big] - d^2\Xi(t)\Xi''(t) + 2\int_0^d u\big(\widetilde{W}(u,t) - \widetilde{W}(0,t)\big) \mathrm{d}u,$$

while $\frac{2}{d^2}\int_0^d u\,\mathrm{sinc} _ {\mathrm{hyp}}(2u y)\,\mathrm{d}u = \mathrm{sinc} _ {\mathrm{hyp}}^2(d y)$ multiplies each Wigner shift $y > 0$ by the contractive filter ratio

$$\mathcal{F} _ {\mathrm{int}}(2d y) := \frac{\mathrm{sinc} _ {\mathrm{hyp}}^2(d y)}{\mathrm{sinc} _ {\mathrm{hyp}}(2d y)} = \frac{\tanh(d y)}{d y} \in (0, 1) \qquad (\forall\, d y > 0).$$

## Summary of Quantitative Diagnostics

| Verification Tier | Domain / Scope | Key Quantity / Diagnostic | Verified Result |
| :--- | :--- | :--- | :--- |
| **Tier 1A: Harmonic Boundary** | $d = 0$, $t \in [14, 90]$ | Max residual of $\Delta R = \Delta I = 0$ and $I(0,t) = \partial_d R(0,t) = 0$ | $1.77 \times 10^{-50}$ (`mp.dps = 50`) |
| **Tier 1B: Curvature & IVT** | $\gamma_1, \dots, \gamma _ {15}$ | $\kappa(\gamma_1) = \Xi''(\gamma_1)/\Xi'(\gamma_1)$ and rigorous `mpmath.iv` sign enclosure | $\kappa(\gamma_1) = -1.1592611550$; all $15$ enclosed $< 0$ (`iv.dps = 55`) |
| **Tier 2: Chamber Tracking** | $\Omega_1, \dots, \Omega _ {25}$, $d \in (0, 1.65]$ | Wall growth $\lvert R(d _ {\mathrm{Euler}})\rvert/\lvert\Xi(\tau_k)\rvert$ and grid sign check | Growth $1.81\times$ to $6.20\times$ across $25$ tracked walls |
| **Tier 3A: Dichotomy Models** | $\Xi _ {\mathrm{hyp}}(z; d_0)$, $d_0 \in \lbrace 0.25, 1.30\rbrace$ | Boundary $L_1(\tau _ {\star}) < 0$ ($d_0=0.25$) vs interior saddle ($d_0=1.30$) | $\tau _ {\star} \approx 17.8716$ ($L_1 < 0$); $d _ {\mathrm{crit}} \approx 0.560540$ |
| **Tier 3B: Rolle Turning Point** | $(d _ {\star}, t _ {\star}) = (0.25, 14.20)$ | Interior Rolle turning point $d _ {\mathrm{peak}} \in (0, d _ {\star})$ and integral residual | $d _ {\mathrm{peak}} = 0.1342212372$; residual $5.22 \times 10^{-54}$ |
| **Tier 3C: Discrete Grid Scan** | $t \in [14, 1000]$, $60{,}000$ points | Mean ratio $\widetilde{\mathcal{E}}(d,t)/\widetilde{W}(d,t)$ ($d = 0.05$ to $0.35$) and $\min \mathcal{R} _ {\mathrm{sq}}$ | $77.19\times$ ($d=0.05$), $2.11\times$ ($d=0.35$); $\min \mathcal{R} _ {\mathrm{sq}} = 0.6544$ |

## Repository Structure

```text
paper3-harmonic-nodal-chambers/
├── paper/
│   ├── paper3_harmonic_nodal_chambers.tex
│   ├── paper3_harmonic_nodal_chambers.pdf
│   └── figures/
│       ├── fig1_harmonic_chladni_chambers_and_curvature.pdf
│       ├── fig1_harmonic_chladni_chambers_and_curvature.png
│       ├── fig2_transverse_integral_law_and_lowpass.pdf
│       └── fig2_transverse_integral_law_and_lowpass.png
├── scripts/
│   └── verify_paper3_harmonic_nodal_chambers.py
├── .agents/
│   └── skills/
│       └── harmonic-nodal-chambers-xi/
│           └── SKILL.md
├── AGENT_SKILL_MANIFEST.json
├── CITATION.cff
├── .zenodo.json
├── LICENSE
└── README.md
```

## Reproducing All Diagnostics and Figures

Requires Python 3.10+ with `mpmath`, `numpy`, `scipy`, `matplotlib`, and `torch` (optional CUDA acceleration). Run from the repository root:

```bash
python scripts/verify_paper3_harmonic_nodal_chambers.py
```
