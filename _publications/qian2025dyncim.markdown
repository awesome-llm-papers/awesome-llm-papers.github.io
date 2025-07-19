---
layout: publication
title: 'Dyncim: Dynamic Curriculum For Imbalanced Multimodal Learning'
authors: Qian et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: qian2025dyncim
citations: 172
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.06456'}]
tags: [ICCV, Tools, Evaluation, Security, Multimodal Models, Datasets, Merging]
---
Multimodal learning integrates complementary information from diverse
modalities to enhance the decision-making process. However, the potential of
multimodal collaboration remains under-exploited due to disparities in data
quality and modality representation capabilities. To address this, we introduce
DynCIM, a novel dynamic curriculum learning framework designed to quantify the
inherent imbalances from both sample and modality perspectives. DynCIM employs
a sample-level curriculum to dynamically assess each sample's difficulty
according to prediction deviation, consistency, and stability, while a
modality-level curriculum measures modality contributions from global and
local. Furthermore, a gating-based dynamic fusion mechanism is introduced to
adaptively adjust modality contributions, minimizing redundancy and optimizing
fusion effectiveness. Extensive experiments on six multimodal benchmarking
datasets, spanning both bimodal and trimodal scenarios, demonstrate that DynCIM
consistently outperforms state-of-the-art methods. Our approach effectively
mitigates modality and sample imbalances while enhancing adaptability and
robustness in multimodal learning tasks. Our code is available at
https://github.com/Raymond-Qiancx/DynCIM.