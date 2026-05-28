---
title: "Finding Most Influential Sets"
collection: research
category: manuscripts
order: 1
permalink: /publication/2026-finding-most-influential-sets
excerpt: 'This paper presents an efficient algorithm to detect maximally influencial in linear regression and proposes consistency criteria for this to hold in double/debiased ML.'
authors: "Konrad, L.D., [Kuschnig, N.](https://www.kuschnig.eu/)"
date: 2026-07-05
venue: 'Proceedings of the International Conference on Machine Learning (ICML)'
paperurl: 'http://arxiv.org/abs/2510.20372'
citation: 'Konrad, L.D., Kuschnig, N. (2026). &quot; Finding Most Influential Sets.&quot; <i>Proceedings of the International Conference on Machine Learning (ICML)</i>.'
---
**Abstract:** Identifying \emph{most influential sets} (MIS) --- size-k subsets whose removal maximally changes a target estimand --- is typically infeasible because it requires searching over n choose k subsets.
For estimands with linear-fractional leave-set-out effects, we show that MIS selection reduces to a one-parameter sequence of top-k problems.
Dinkelbach's method yields an algorithm with O(n) cost per iteration and finite termination.
For fixed residualized inputs, the algorithm returns a globally optimal set for the univariate ratio objective, including the oracle-residualized partial linear model.
With estimated nuisance functions, uniform denominator and generated-score stability imply approximation to the first-order oracle orthogonal-score objective; exact set recovery follows under a separation condition.
Simulations and applications show that the method recovers exact MIS that were previously computationally inaccessible.

**Status:** forthcoming

**Co-author:** [Nikolas Kuschnig](https://www.kuschnig.eu/)
