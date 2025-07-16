---
title: "Wideband Joint Elevation-Azimuth Angle Estimation Based on Multiple Frequency Model and Atomic Norm Minimization"
collection: publications
category: manuscripts
excerpt: '*Keywords*: 2-D direction-of-arrival (DOA) estimation, atomic norm minimization (ANM), multiple frequency model, wideband DOA estimation'
permalink: /publication/2DMFANM_J
date: 2025-04-01
venue: 'IEEE Transactions on Instrumentation and Measurement'
paperurl: '/files/TIM.pdf'
---
**Abstract**: Estimating the direction of arrival (DOA) has been a crucial problem in a wide range of applications. Current research predominantly focuses on narrow-band, 1-D signals, which are not directly applicable to practical scenarios involving wideband and multidimensional signals. To deal with this
drawback, we propose a 2-D multiple frequency atomic norm
minimization (2DMFANM) algorithm to estimate the elevation
and azimuth angles of wideband signals in a grid-less manner.
To be specific, we exploit the multiple frequency model to describe
the wideband signals and derive the corresponding signal model.
Based on the structure of the signal model, we formulated
an atomic norm minimization (ANM) problem that allows for
the gridless joint estimation of elevation and azimuth angles.
The ANM problem is further converted into semidefinite programming (SDP) via analysis of the dual problem. To reduce
the computational burden that hinders the deployment of
2DMFANM, we propose two fast algorithms called 2DMFDANM
and 2DMFANM_SizeRedu. Specifically, 2DMFDANM reduces
the size of the original algorithm by decoupling the information of spatial angular frequencies, while 2DMFANM_SizeRedu
achieves fast speed by removing the redundancy in the original
algorithm. Theoretical and numerical analyses indicate that these
two algorithms significantly enhance the speed of computation
with minor degradation in the estimation accuracy. Numerical
simulations and experimental data analysis demonstrate the
superior performance of the proposed methods compared to
state-of-the-art algorithms.
