---
layout: publication
title: 'PEVL: Position-enhanced Pre-training And Prompt Tuning For Vision-language
  Models'
authors: Yuan Yao et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 21
bibkey: yao2022position
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11169'}, {name: Code,
    url: 'https://github.com/thunlp/PEVL'}]
tags: [Language Modeling, Has Code, Tools, Multimodal Models, Prompting, Pre-Training,
  Efficiency and Optimization, Training Techniques]
---
Vision-language pre-training (VLP) has shown impressive performance on a wide
range of cross-modal tasks, where VLP models without reliance on object
detectors are becoming the mainstream due to their superior computation
efficiency and competitive performance. However, the removal of object
detectors also deprives the capability of VLP models in explicit object
modeling, which is essential to various position-sensitive vision-language (VL)
tasks, such as referring expression comprehension and visual commonsense
reasoning. To address the challenge, we introduce PEVL that enhances the
pre-training and prompt tuning of VLP models with explicit object position
modeling. Specifically, PEVL reformulates discretized object positions and
language in a unified language modeling framework, which facilitates explicit
VL alignment during pre-training, and also enables flexible prompt tuning for
various downstream tasks. We show that PEVL enables state-of-the-art
performance of detector-free VLP models on position-sensitive tasks such as
referring expression comprehension and phrase grounding, and also improves the
performance on position-insensitive tasks with grounded inputs. We make the
data and code for this paper publicly available at
https://github.com/thunlp/PEVL.