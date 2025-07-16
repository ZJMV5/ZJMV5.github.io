---
title: "Fast constrained area DOA estimation based on atomic norm minimization (in Chinese)"
collection: publications
category: manuscripts
excerpt: 'This paper is accepted by ACTA ACUSTICA (Chinese version). *Keywords*: Constrained area, Direction of arrival estimation, Atomic norm minimization, Semi-definite programming, Primal-dual interior point method'
permalink: /publication/CAANM
paperurl: '/files/CAANM.pdf'
date: 2025-05-13
venue: 'ACTA ACUSTICA, Chinese version'
---

**Abstract**: When the directions of arrival (DOAs) of the targets are constrained to a specific angular sector, the computational complexity can be reduced by restricting the DOA search area within this target region. However, due to the application constraints of the bounded lemma, conventional atomic norm minimization (ANM)-based DOA estimation methods cannot impose angular search area constraints directly. This limitation necessitates exhaustive search over the entire angular domain, resulting in substantial computational redundancy. To address this challenge, this paper proposes a dual-variable processing framework involving bandpass filtering and downsampling. This approach enables the conversion of dual trigonometric polynomial inequality constraints into semidefinite constraints through the bounded lemma, thereby transforming the dual problem into a semidefinite programming (SDP) formulation. Consequently, an ANM-based DOA estimation method with angular sector constraints is developed. To enhance computational efficiency, we further propose a fast algorithm that leverages primal-dual interior-point methods to accelerate computation. Simulation results demonstrate that, compared to the original ANM algorithm, the proposed constrained area ANM algorithm significantly reduces computational time; additionally, the proposed fast algorithm further increases computation speed while maintaining the same estimation accuracy as the original algorithm.
