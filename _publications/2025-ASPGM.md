---
title: "A Practical Adaptive Subgame Perfect Gradient Method"
collection: publications
category: conferences
permalink: /publication/ASPGM
excerpt: 'This work presents a new algorithm for smooth convex optimization, the Adaptive Subgame Perfect Gradient Method (ASPGM). At each iteration, ASPGM makes a momentum-type update, optimized dynamically based on a (limited) memory/bundle of past first-order information. ASPGM is linesearch-free, parameter-free, and adaptive, and the core algorithm underlying ASPGM has strong, subgame perfect, non-asymptotic guarantees, providing certificates of solution quality, resulting in simple stopping criteria and restarting conditions.'
date: 2025-10-26
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2510.21617'
citation: 'Alan Luner, Benjamin Grimmer. (2025). &quot;A Practical Adaptive Subgame Perfect Gradient Method.&quot; <i>ArXiv Preprint 2510.21617</i>.'
---

We present a performant gradient method for smooth convex optimization, drawing inspiration from several recent advances in the field. Our algorithm, the Adaptive Subgame Perfect Gradient Method (ASPGM) is based on the notion of subgame perfection, attaining a dynamic strengthening of minimax optimality. At each iteration, ASPGM makes a momentum-type update, optimized dynamically based on a (limited) memory/bundle of past first-order information. ASPGM is linesearch-free, parameter-free, and adaptive due to its use of recently developed auto-conditioning, restarting, and preconditioning ideas. We show that ASPGM is competitive with state-of-the-art L-BFGS methods on a wide range of smooth convex problems. Unlike quasi-Newton methods, however, our core algorithm underlying ASPGM has strong, subgame perfect, non-asymptotic guarantees, providing certificates of solution quality, resulting in simple stopping criteria and restarting conditions.
