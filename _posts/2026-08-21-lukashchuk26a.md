---
title: Composing Non-Conjugate Factor Graphs with Closed-Form Variational Inference
abstract: 'Stacking probabilistic building blocks into deeper architectures typically
  breaks closed-form inference. We show that closed-form inference can be preserved.
  We identify five factor-graph primitives: a bilinear factor, an exponential link,
  a Gamma prior, a Gaussian likelihood, and an equality node, and prove that any model
  composed from them admits closed-form variational message passing. The construction
  works because each primitive preserves a small set of message families: under mean-field
  factorization, messages on Gaussian variables remain Gaussian and messages on precision
  variables remain Gamma, while the only non-conjugate interface, the exponential
  link, remains tractable through the Gaussian moment-generating function and the
  sufficient statistics of the Gamma family. We demonstrate composition at increasing
  depth, from static ensembles through input-dependent gating to split-branch routing,
  and show that stacking routing layers encodes arbitrary decision trees, establishing
  universal function approximation with closed-form inference. Applied to ensemble
  time-series forecasting, the framework yields a Bayesian mixture of experts in which
  gating functions are inferred rather than learned, providing calibrated uncertainty
  over expert selection across five benchmark datasets.'
openreview: fi4qX94LI8
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lukashchuk26a
month: 0
tex_title: Composing Non-Conjugate Factor Graphs with Closed-Form Variational Inference
firstpage: 102
lastpage: 123
page: 102-123
order: 102
cycles: false
bibtex_author: Lukashchuk, Mykola and Yemets, Kyrylo and Kouw, Wouter M. and Bagaev,
  Dmitry and Senoz, Ismail and Beck, Jeff and de Vries, Bert
author:
- given: Mykola
  family: Lukashchuk
- given: Kyrylo
  family: Yemets
- given: Wouter M.
  family: Kouw
- given: Dmitry
  family: Bagaev
- given: Ismail
  family: Senoz
- given: Jeff
  family: Beck
- given: Bert
  family: Vries
  prefix: de
date: 2026-08-21
address:
container-title: Proceedings of the 2nd International Conference on Probabilistic
  Numerics
volume: '341'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 8
  - 21
pdf: https://raw.githubusercontent.com/mlresearch/v341/main/assets/lukashchuk26a/lukashchuk26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
