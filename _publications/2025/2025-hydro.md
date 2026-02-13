---
title:          "Hybrid Cross-domain Robust Reinforcement Learning"
date:           2025-05-15 
selected:       false
pub:            "European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD)"
pub_ab:         "ECML-PKDD"
pub_date:       "2025"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  Robust reinforcement learning (RL) aims to learn policies that remain effective despite uncertainties in its environment, which frequently arise in real-world applications due to variations in environment dynamics. The robust RL methods learn a robust policy by maximizing value under the worst-case models within a predefined uncertainty set. Offline robust RL algorithms are particularly promising in scenarios where only a fixed dataset is available and new data cannot be collected. However, these approaches often require extensive offline data, and gathering such datasets for specific tasks in specific environments can be both costly and time-consuming. Using an imperfect simulator offers a faster, cheaper, and safer way to collect data for training, but it can suffer from dynamics mismatch. In this paper, we introduce HYDRO, the first Hybrid Cross-Domain Robust RL framework designed to address these challenges. HYDRO utilizes an online simulator to complement the limited amount of offline datasets in the non-trivial context of robust RL. By measuring and minimizing performance gaps between the simulator and the worst-case models in the uncertainty set, HYDRO employs novel uncertainty filtering and prioritized sampling to select the most relevant and reliable simulator samples. Our extensive experiments demonstrate HYDRO's superior performance over existing methods across various tasks, underscoring its potential to improve sample efficiency in offline robust RL.

# cover:          /assets/images/covers/cover1.jpg
authors:
  - Linh Le
  - Minh Hoang Nguyen
  - Hung Le
  - Hung The Tran
  - Sunil Gupta
links:
  Pdf: https://arxiv.org/pdf/2505.23003
  # Code: https://github.com
---