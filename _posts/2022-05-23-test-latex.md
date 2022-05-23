---
  usemathjax: true
---

Given a finite set of probability density functions $p_1(x), p_1(x), \dots, p_n(x)$ and weights $w_1, w_2, \dots, w_n$ such that $w_i \geq 0$ and $\sum_i w_i = 1$. The mixture model $f$ can be represented as $$f(x) = \sum\limits_{i=1}^n w_ip_i(x).$$

We call a (finite) real number $\alpha$ is simple order if $\alpha > 0$ and $\alpha \neq 1$. The values $0,1,$ and $\infty$ are called extended orders.

For any simple order $\alpha$, the Rényi divergence of probability measure $P$ from $Q$ is defined as
$$\begin{aligned} D_{\alpha}(P||Q) &= \frac{1}{\alpha - 1}\ln{\int p(x)^{\alpha}q(x)^{1-\alpha}}dx \\
                                   &= \frac{1}{\alpha - 1}\ln{\mathbb{E}_q(p/q)^\alpha}. \end{aligned}$$
