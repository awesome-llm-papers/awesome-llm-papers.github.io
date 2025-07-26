---
layout: publication
title: 'Guardreasoner: Towards Reasoning-based LLM Safeguards'
authors: Yue Liu, Hongcheng Gao, Shengfang Zhai, Jun Xia, Tianyi Wu, Zhiwei Xue, Yulin
  Chen, Kenji Kawaguchi, Jiaheng Zhang, Bryan Hooi
conference: No Venue
year: 2025
bibkey: liu2025guardreasoner
additional_links: [{name: Code, url: 'https://github.com/yueliu1999/GuardReasoner/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/679c4ac6e2c0dbf282597d80'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.18492'}]
tags: ["Applications", "Ethics & Fairness", "Has Code"]
short_authors: Liu et al.
---
As LLMs increasingly impact safety-critical applications, ensuring their safety using guardrails remains a key challenge. This paper proposes GuardReasoner, a new safeguard for LLMs, by guiding the guard model to learn to reason. Concretely, we first create the GuardReasonerTrain dataset, which consists of 127K samples with 460K detailed reasoning steps. Then, we introduce reasoning SFT to unlock the reasoning capability of guard models. In addition, we present hard sample DPO to further strengthen their reasoning ability. In this manner, GuardReasoner achieves better performance, explainability, and generalizability. Extensive experiments and analyses on 13 benchmarks of 3 guardrail tasks demonstrate its superiority. Remarkably, GuardReasoner 8B surpasses GPT-4o+CoT by 5.74% and LLaMA Guard 3 8B by 20.84% F1 score on average. We release the training data, code, and models with different scales (1B, 3B, 8B) of GuardReasoner : https://github.com/yueliu1999/GuardReasoner/.

https://huggingface.co/discussions/paper/679c4ac6e2c0dbf282597d80