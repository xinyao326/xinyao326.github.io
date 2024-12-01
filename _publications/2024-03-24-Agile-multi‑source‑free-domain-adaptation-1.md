---
title: "Agile multi‑source‑free domain adaptation"
collection: publications
category: conferences
permalink: /publication/2024-03-24-Agile-multi‑source‑free-domain-adaptation-1
excerpt: 'Multi-source-free domain adaptation (MSFDA) with high data and computational efficiency'
date: 2024-03-24
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'
paperurl: 'http://xinyao326.github.io/files/24_AAAI_Agile_Multi-Source-Free_Domain_Adaptation.pdf'
#citation: 'X. Li, J. Li, F. Li, L. Zhu, and K. Lu. (2024). &quot;Agile multi‑source‑free domain adaptation.&quot; <i>Proceedings of the AAAI Conference on Artificial Intelligence</i>. '
---

Efficiently utilizing rich knowledge in pretrained models has become a critical topic in the era of large models. This work focuses on adaptively utilize knowledge from multiple source-pretrained models to an unlabeled target domain without accessing the source data. Despite being a practically useful setting, existing methods require extensive parameter tuning over each source model, which is computationally expensive when facing abundant source domains or larger source models. To address this challenge, we propose a novel approach which is free of the parameter tuning over source backbones. Our technical contribution lies in the Bi-level ATtention ENsemble (Bi-ATEN) module, which learns both intra-domain weights and inter-domain ensemble weights to achieve a fine balance between instance specificity and domain consistency. By slightly tuning source bottlenecks, we achieve comparable or even superior performance on a challenging benchmark DomainNet with less than 3% trained parameters and 8 times of throughput compared with SOTA method. Furthermore, with minor modifications, the proposed module can be easily equipped to existing methods and gain more than 4% performance boost.
