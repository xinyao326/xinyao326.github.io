---
title: "Domain adaptive remaining useful life prediction with transformer"
collection: publications
category: manuscripts
permalink: /publication/2022-08-22-domain-adaptive
excerpt: 'Domain adaptative remaining useful life (RUL) prediction for machines.'
date: 2022-08-22
venue: 'IEEE Transactions on Instrumentation and Measurement'
paperurl: 'http://xinyao326.github.io/files/22_TIM_Domain_Adaptive_Remaining_Useful_Life_Prediction_With_Transformer.pdf'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'X. Li, J. Li, L. Zuo, L. Zhu, and H. T. Shen. (2022). &quot;Domain adaptive remaining useful life prediction with transformer.&quot; <i>IEEE Transactions on Instrumentation and Measurement</i>.'
---

Prognostic health management (PHM) has become a crucial part in building highly automated systems, whose primary task is to precisely predict the remaining useful life (RUL) of the system. Recently, deep models including convolutional neural network (CNN) and long short-term memory (LSTM) have been widely used to predict RUL. However, these models generally require sufficient labeled training data to guarantee fair performance, whereas a limited amount of labeled data overwhelmed by the abundance of unlabeled ones is the normality in industry, and the cost of full data annotation can be unaffordable. To attack this challenge, domain adaptation seeks to transfer the knowledge from a well-labeled source domain to another unlabeled target domain by mitigating their domain gap. In this article, we leverage domain adaptation for RUL prediction and propose a novel method by aligning distributions at both the feature level and the semantic level. The proposed method facilitates a large improvement of model performance and faster convergence. Besides, we propose to use the transformer as the backbone, which can capture long-term dependency more efficiently than the widely used recurrent neural network (RNN), and is thus critical for boosting the robustness of the model. We test our model on the commercial modular aero-propulsion system simulation (CMAPSS) dataset and its newly published variant new CMAPSS (N-CMAPSS) provided by National Aeronautics and Space Administration (NASA), achieving state-of-the-art results on both source-only RUL prediction and domain adaptive RUL prediction tasks.
