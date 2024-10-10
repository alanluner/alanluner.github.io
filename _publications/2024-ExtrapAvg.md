---
title: "On Averaging and Extrapolation for Gradient Descent"
collection: publications
category: conferences
permalink: /publication/ExtrapAvgGD
excerpt: 'This work considers the effect of averaging and extrapolation of the iterates of gradient descent in smooth convex optimization. We show that for several common stepsize sequences, averaging cannot improve gradient descent''s worst-case performance. In contrast, we prove a conceptually simple and computationally cheap extrapolation scheme strictly improves the worst-case convergence rate: when initialized at the origin, reporting $(1+1/\sqrt{16N\log(N)})x_N$ rather than $x_N$ improves the best possible worst-case performance by the same amount as conducting $O(\sqrt{N/\log(N)})$ more gradient steps.'
date: 2024-02-26
venue: 'ArXiv Preprint'
paperurl: 'https://arxiv.org/abs/2402.12493'
citation: 'Alan Luner, Benjamin Grimmer. (2024). &quot;On Averaging and Extrapolation for Gradient Descent.&quot; <i>ArXiv Preprint</i>.'
---

This work considers the effect of averaging, and more generally extrapolation, of the iterates of gradient descent in smooth convex optimization. After running the method, rather than reporting the final iterate, one can report either a convex combination of the iterates (averaging) or a generic combination of the iterates (extrapolation). For several common stepsize sequences, including recently developed accelerated periodically long stepsize schemes, we show averaging cannot improve gradient descent's worst-case performance and is, in fact, strictly worse than simply returning the last iterate. In contrast, we prove a conceptually simple and computationally cheap extrapolation scheme strictly improves the worst-case convergence rate: when initialized at the origin, reporting $(1+1/\sqrt{16N\log(N)})x_N$ rather than $x_N$ improves the best possible worst-case performance by the same amount as conducting $O(\sqrt{N/\log(N)})$ more gradient steps. Our analysis and characterizations of the best-possible convergence guarantees are computer-aided, using performance estimation problems. Numerically, we find similar (small) benefits from such simple extrapolation for a range of gradient methods.
