---
layout: publication
title: 'Revisiting Epistemic Markers In Confidence Estimation: Can Markers Accurately
  Reflect Large Language Models'' Uncertainty?'
authors: Liu et al.
conference: Proceedings of the 47th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2025
bibkey: liu2025revisiting
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.24778'}]
tags: [Reinforcement Learning, SIGIR, Datasets]
---
As large language models (LLMs) are increasingly used in high-stakes domains, accurately assessing their confidence is crucial. Humans typically express confidence through epistemic markers (e.g., "fairly confident") instead of numerical values. However, it remains unclear whether LLMs consistently use these markers to reflect their intrinsic confidence due to the difficulty of quantifying uncertainty associated with various markers. To address this gap, we first define marker confidence as the observed accuracy when a model employs an epistemic marker. We evaluate its stability across multiple question-answering datasets in both in-distribution and out-of-distribution settings for open-source and proprietary LLMs. Our results show that while markers generalize well within the same distribution, their confidence is inconsistent in out-of-distribution scenarios. These findings raise significant concerns about the reliability of epistemic markers for confidence estimation, underscoring the need for improved alignment between marker based confidence and actual model uncertainty. Our code is available at https://github.com/HKUST-KnowComp/MarCon.