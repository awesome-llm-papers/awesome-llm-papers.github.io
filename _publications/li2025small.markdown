---
layout: publication
title: Small Models Struggle To Learn From Strong Reasoners
authors: Yuetai Li, Xiang Yue, Zhangchen Xu, Fengqing Jiang, Luyao Niu, Bill Yuchen
  Lin, Bhaskar Ramasubramanian, Radha Poovendran
conference: No Venue
year: 2025
bibkey: li2025small
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.12143'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Li et al.
---
Large language models (LLMs) excel in complex reasoning tasks, and distilling their reasoning capabilities into smaller models has shown promise. However, we uncover an interesting phenomenon, which we term the Small Model Learnability Gap: small models (leq3B parameters) do not consistently benefit from long chain-of-thought (CoT) reasoning or distillation from larger models. Instead, they perform better when fine-tuned on shorter, simpler reasoning chains that better align with their intrinsic learning capacity. To address this, we propose Mix Distillation, a simple yet effective strategy that balances reasoning complexity by combining long and short CoT examples or reasoning from both larger and smaller models. Our experiments demonstrate that Mix Distillation significantly improves small model reasoning performance compared to training on either data alone. These findings highlight the limitations of direct strong model distillation and underscore the importance of adapting reasoning complexity for effective reasoning capability transfer.

https://huggingface.co/discussions/paper/67b4d05b9f8a8ab6614503cb