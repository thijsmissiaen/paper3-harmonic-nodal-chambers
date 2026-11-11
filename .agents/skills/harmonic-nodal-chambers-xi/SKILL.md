---
name: harmonic-nodal-chambers-xi
description: Analytical and geometric reference skill for Riemann's Xi-function covering universal harmonic nodal identities, the two-mechanism dichotomy for off-critical zeros, the Csordas-Smith-Varga zero-curve curvature jet kappa(gamma_k) = Xi''(gamma_k)/Xi'(gamma_k), and the canonical Transverse Integral Identity with its hyperbolic filter ratio F_int(2dy) = tanh(dy)/(dy).
---

# Harmonic Nodal Geometry, Zero-Curve Curvature, and the Transverse Integral Identity for Riemann's $\Xi$-Function

This skill summarizes the exact harmonic identities, conditional monotonicity statements, explicit counterexample obstructions, and verification procedures established in:

> **Thijs Missiaen** (ORCID: `0009-0007-3678-0810`), *Harmonic Nodal Geometry, Zero-Curve Curvature, and the Transverse Integral Identity for Riemann's Xi-Function* (2026), 15 pages, DOI: `10.5281/zenodo.23641700`.

## 1. Universal Harmonic Structure and Euler–Stirling Boundary in $\sigma > 1$

For any non-constant entire function $f(z)$ real on $\mathbb{R}$, write $z = t - \mathrm{i}d$ ($s = \frac{1}{2} + d + \mathrm{i}t$) and $f(t - \mathrm{i}d) = R_f(d,t) + \mathrm{i}I_f(d,t)$. Everywhere on $\mathbb{R}^2$:

$$\frac{\partial R_f}{\partial d} = \frac{\partial I_f}{\partial t}, \qquad \frac{\partial I_f}{\partial d} = -\frac{\partial R_f}{\partial t}, \qquad \Delta R_f = \frac{\partial^2 R_f}{\partial d^2} + \frac{\partial^2 R_f}{\partial t^2} = 0, \qquad \Delta I_f = \frac{\partial^2 I_f}{\partial d^2} + \frac{\partial^2 I_f}{\partial t^2} = 0.$$

1. **Critical-line boundary conditions:** $I_f(0,t) \equiv 0$, $\partial_d R_f(0,t) \equiv 0$, and $\int _ {t_1}^{t_2} R_f(0,t) \partial_d R_f(0,t) \mathrm{d}t \equiv 0$.
2. **Orthogonal departure of imaginary nodal curves:** Because $\widetilde{I}_f(d,t) := I_f(d,t)/d = -f'(t) + \frac{1}{6}f'''(t)d^2 - \frac{1}{120}f^{(5)}(t)d^4 + \mathcal{O}(d^6)$, transverse curves $\Gamma \subset \lbrace I_f(d,t) = 0, d > 0\rbrace$ meet $d = 0$ exclusively at real critical points $f'(\tau) = 0$, with vertex curvature $\kappa _ \Gamma(\tau) = t _ \Gamma''(0) = \frac{f'''(\tau)}{3 f''(\tau)}$ whenever $f''(\tau) \neq 0$. For Riemann's $\Xi(t)$, the first two positive critical-line extrema are $\tau_1 \approx 15.58570859$ and $\tau_2 \approx 22.09797728$.
3. **Exclusion of compact loops and Euler–Stirling boundary in $\sigma > 1$:** By $\Delta I_f = 0$, no branch of $I_f = 0$ encloses a bounded domain. For $f = \Xi$ in the Euler-product half-plane $d > \frac{1}{2}$ ($\sigma = \frac{1}{2} + d > 1$, outside the critical strip), $\frac{W(d,t)}{\lvert\Xi(t-\mathrm{i}d)\rvert^2} = \partial_t\arg\Xi(t-\mathrm{i}d) \ge \mathcal{A}(d,t) + \frac{\zeta'(1/2+d)}{\zeta(1/2+d)} > 0$ holds unconditionally for all $d > d _ {\mathrm{Euler}}(t) > \frac{1}{2}$, where $d _ {\mathrm{Euler}}(t) = \frac{1}{2} + [\frac{1}{2}\ln\frac{t}{2\pi} + \gamma _ {\mathrm{E}} + \mathcal{O}((\ln t)^{-1})]^{-1} \to \frac{1}{2}^+$.

## 2. Cauchy–Riemann Arc-Length Equation, Two-Mechanism Dichotomy, and Zero-Curve Curvature

Along any smooth segment of $\Gamma \subset \lbrace I_f = 0, d > 0\rbrace$ parameterized by arc length $s > 0$ departing from $(0,\tau)$ ($f(\tau) \neq 0$, $f''(\tau) \neq 0$) and free of critical points $f'(z) = 0$ and zeros $R_f = 0$:

$$\frac{\mathrm{d}}{\mathrm{d}s}\lvert R_f(d(s), t(s))\rvert = \mathrm{sgn}\big(L_1(f;\tau)\big)\,\lvert\nabla I_f(d(s), t(s))\rvert = \mathrm{sgn}\big(L_1(f;\tau)\big)\,\lvert f'(t(s) - \mathrm{i}d(s))\rvert,$$

where $L_1(f;\tau) = -f(\tau)f''(\tau)$ is the classical first Laguerre expression (Jensen, 1913; Csordas–Varga, 1990). Consequently, an off-critical zero $(d _ {\star}, t _ {\star})$ ($d _ {\star} > 0$) on $\Gamma$ requires **either** (i) a boundary Laguerre violation $L_1(f;\tau) \le 0$ on $d = 0$ (realized by $\Xi _ {\mathrm{hyp}}(z; 0.25)$ at $\tau _ {\star} \approx 17.87156653$) **or** (ii) an interior critical point $f'(z _ {\mathrm{crit}}) = 0$ in $d > 0$ (realized by $\Xi _ {\mathrm{hyp}}(z; 1.30)$ at $(d _ {\mathrm{crit}}, t _ {\mathrm{crit}}) \approx (0.56054034, 18.66151713){}$). Ruling out interior critical points of $\Xi$ in $d > 0$ is equivalent to RH (Lagarias, 1999; distinct from Speiser's theorem $\zeta'(s) \neq 0$ in $0 < \sigma < \frac{1}{2}$).

Around any simple real zero $\gamma_k$, the real nodal curve $\mathcal{R} _ k := \lbrace (d, t _ {\mathcal{R} _ k}(d)) : R_f(d,t) = 0\rbrace$ satisfies

$$t _ {\mathcal{R} _ k}(d) - \gamma_k = c _ {\mathrm{par}}(\gamma_k) d^2 + c _ {\mathrm{quart}}(\gamma_k) d^4 + \mathcal{O}(d^6), \qquad \kappa(\gamma_k) := t _ {\mathcal{R} _ k}''(0) = \frac{f''(\gamma_k)}{f'(\gamma_k)}, \qquad c _ {\mathrm{par}}(\gamma_k) = \frac{1}{2}\kappa(\gamma_k),$$

matching for $f = \Xi$ the de Bruijn–Newman zero-velocity ratio of Csordas, Smith, and Varga (1994).

## 3. Canonical Transverse Wronskian, Integral Identity, and Obstructions

Under canonical normalization $W(d,t) = \frac{1}{2}\partial_d\lvert\Xi(t-\mathrm{i}d)\rvert^2 = 16\int_0^\infty y\sinh(2d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y$ and $\widetilde{W}(d,t) = W(d,t)/d = 32\int_0^\infty y^2\,\mathrm{sinc} _ {\mathrm{hyp}}(2d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y$ with $I _ {\mathrm{Wig}}(y,t) = \int _ {-\infty}^\infty \Phi(\frac{x+y}{2})\Phi(\frac{x-y}{2})\cos(2t x)\,\mathrm{d}x$:

$$\lvert\Xi(t - \mathrm{i}d)\rvert^2 = \lvert\Xi(t)\rvert^2 + 2\int_0^d u \widetilde{W}(u,t) \mathrm{d}u, \qquad \frac{2}{d^2}\int_0^d u \widetilde{W}(u,t) \mathrm{d}u = 32\int_0^\infty y^2\,\mathrm{sinc} _ {\mathrm{hyp}}^2(d y)\,I _ {\mathrm{Wig}}(y,t)\,\mathrm{d}y,$$

with filter ratio $\mathcal{F} _ {\mathrm{int}}(2d y) = \frac{\mathrm{sinc} _ {\mathrm{hyp}}^2(d y)}{\mathrm{sinc} _ {\mathrm{hyp}}(2d y)} = \frac{\tanh(d y)}{d y} \in (0, 1)$ for $d y > 0$. Because $I _ {\mathrm{Wig}}(y,t)$ oscillates in sign and universal harmonic laws also hold for Davenport–Heilbronn functions, neither nodal geometry nor the $\mathrm{sinc} _ {\mathrm{hyp}}^2$ kernel yields unconditional global positivity without arithmetic Euler-product input inside $0 < d < \frac{1}{2}$ (where Voronin universality rules out triangle-inequality majorants).

## 4. Verification Procedure

```bash
python scripts/verify_paper3_harmonic_nodal_chambers.py
```

Reproduces all 50-digit local jets, rigorous `mpmath.iv` curvature sign enclosures across $\gamma_1, \dots, \gamma _ {15}$, tracking across $\Omega_1, \dots, \Omega _ {25}$, both off-critical dichotomy models, and the 300-DPI figures in `paper/figures/`.
