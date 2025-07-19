---
layout: publication
title: 'Geollava-8k: Scaling Remote-sensing Multimodal Large Language Models To 8K
  Resolution'
authors: Wang et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW)
year: 2025
bibkey: wang2025geollava
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.21375'}]
tags: [ICCV, Training Techniques, Tools, Efficiency And Optimization, Reinforcement
    Learning, Multimodal Models, Pruning, Datasets]
---
Ultra-high-resolution (UHR) remote sensing (RS) imagery offers valuable data for Earth observation but pose challenges for existing multimodal foundation models due to two key bottlenecks: (1) limited availability of UHR training data, and (2) token explosion caused by the large image size. To address data scarcity, we introduce SuperRS-VQA (avg. 8,376\\(\times\\)8,376) and HighRS-VQA (avg. 2,000\\(\times\\)1,912), the highest-resolution vision-language datasets in RS to date, covering 22 real-world dialogue tasks. To mitigate token explosion, our pilot studies reveal significant redundancy in RS images: crucial information is concentrated in a small subset of object-centric tokens, while pruning background tokens (e.g., ocean or forest) can even improve performance. Motivated by these findings, we propose two strategies: Background Token Pruning and Anchored Token Selection, to reduce the memory footprint while preserving key semantics.Integrating these techniques, we introduce GeoLLaVA-8K, the first RS-focused multimodal large language model capable of handling inputs up to 8K\\(\times\\)8K resolution, built on the LLaVA framework. Trained on SuperRS-VQA and HighRS-VQA, GeoLLaVA-8K sets a new state-of-the-art on the XLRS-Bench.