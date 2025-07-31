---
title: "DmC: Nearest Neighbor Guidance Diffusion Model for Offline Cross-domain Reinforcement Learning"
collection: publications
permalink: /publication/dmc
excerpt: 'Cross-domain offline reinforcement learning (RL) seeks to enhance sample efficiency in offline RL by utilizing additional offline source datasets. A key challenge is to identify and utilize source samples that are most relevant to the target domain. Existing approaches address this challenge by measuring domain gaps through domain classifiers, target transition dynamics modeling, or mutual information estimation using contrastive loss. However, these methods often require large target datasets, which is impractical in many real-world scenarios. In this work, we address cross-domain offline RL under a limited target data setting, identifying two primary challenges: (1) Dataset imbalance, which is caused by large source and small target datasets and leads to overfitting in neural network-based domain gap estimators, resulting in uninformative measurements; and (2) Partial domain overlap, where only a subset of the source data is closely aligned with the target domain. To overcome these issues, we propose DmC, a novel framework for cross-domain offline RL with limited target samples. Specifically, DmC utilizes -nearest neighbor (-NN) based estimation to measure domain proximity without neural network training, effectively mitigating overfitting. Then, by utilizing this domain proximity, we introduce a nearest-neighbor-guided diffusion model to generate additional source samples that are better aligned with the target domain, thus enhancing policy learning with more effective source samples. Through theoretical analysis and extensive experiments in diverse MuJoCo environments, we demonstrate that DmC significantly outperforms state-of-the-art cross-domain offline RL methods, achieving substantial performance gains.'
date: 2025-07-12
venue: 'ECML-PKDD'
paperurl: 'https://arxiv.org/pdf/2507.20499'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
authors: Linh Le Pham Van, Minh Hoang Nguyen, Duc Kieu, Hung Le, Hung The Tran, Sunil Gupta
---

<!-- [](https://repository.vnu.edu.vn/bitstream/VNU_123/137784/1/2020_KY_Node-aware_convolution.pdf) -->