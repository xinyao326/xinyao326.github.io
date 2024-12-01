---
title: "Domain‑agnostic mutual prompting for unsupervised domain adaptation"
collection: publications
category: conferences
permalink: /publication/2024-02-28-domain-agnostic
excerpt: 'Unsupervised domain adaptation (UDA) of vision-language models (e.g., CLIP).'
date: 2024-02-28
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'http://xinyao326.github.io/files/Du_Domain-Agnostic_Mutual_Prompting_for_Unsupervised_Domain_Adaptation_CVPR_2024_paper.pdf'
citation: 'Z. Du, X. Li, F. Li, K. Lu, L. Zhu, and J. Li. (2024). &quot;Domain‑agnostic mutual prompting for unsupervised domain adaptation.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition</i>.'
---

Conventional Unsupervised Domain Adaptation (UDA) strives to minimize distribution discrepancy between domains which neglects to harness rich semantics from data and struggles to handle complex domain shifts. A promising technique is to leverage the knowledge of large-scale pre-trained vision-language models for more guided adaptation. Despite some endeavors current methods often learn textual prompts to embed domain semantics for source and target domains separately and perform classification within each domain limiting cross-domain knowledge transfer. Moreover prompting only the language branch lacks flexibility to adapt both modalities dynamically. To bridge this gap we propose Domain-Agnostic Mutual Prompting (DAMP) to exploit domain-invariant semantics by mutually aligning visual and textual embeddings. Specifically the image contextual information is utilized to prompt the language branch in a domain-agnostic and instance-conditioned way. Meanwhile visual prompts are imposed based on the domain-agnostic textual prompt to elicit domain-invariant visual embeddings. These two branches of prompts are learned mutually with a cross-attention module and regularized with a semantic-consistency loss and an instance-discrimination contrastive loss. Experiments on three UDA benchmarks demonstrate the superiority of DAMP over state-of-the-art approaches.
