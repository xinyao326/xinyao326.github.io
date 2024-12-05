---
title: "Source‑free active domain adaptation via energy‑based locality preserving transfer"
collection: publications
category: conferences
permalink: /publication/2022-10-10-source-free-active
excerpt: 'Proposes and tackle a new transfer setting Source-Free-Active Domain Adaptation (SFADA).'
date: 2022-10-10
venue: 'Proceedings of the 30th ACM international conference on multimedia'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3503161.3548152'
citation: 'X. Li, Z. Du, J. Li, L. Zhu, and K. Lu. (2022). &quot;Source‑free active domain adaptation via energy‑based locality preserving transfer.&quot; <i>Proceedings of the 30th ACM international conference on multimedia</i>.'
---

Unsupervised domain adaptation (UDA) aims at transferring knowledge from one labeled source domain to a related but unlabeled
target domain. Recently, active domain adaptation (ADA) has been
proposed as a new paradigm which significantly boosts performance of UDA with minor additional labeling. However, existing
ADA methods require source data to explicitly measure the domain
gap between the source domain and the target domain, which is
restricted in many real-world scenarios. In this work, we handle
ADA with only a source-pretrained model and unlabeled target
data, proposing a new setting named source-free active domain
adaptation. Specifically, we propose a Locality Preserving Transfer
(LPT) framework which preserves and utilizes locality structures on
target data to achieve adaptation without source data. Meanwhile,
a label propagation strategy is adopted to improve the discriminability for better adaptation. After LPT, unique samples with
insignificant locality structure are identified by an energy-based
approach for active annotation. An energy-based pseudo labeling
strategy is further applied to generate labels for reliable samples.
Finally, with supervision from the annotated samples and pseudo
labels, a well adapted model is obtained. Extensive experiments
on three widely used UDA benchmarks show that our method is
comparable or superior to current state-of-the-art active domain
adaptation methods even without access to source data.
