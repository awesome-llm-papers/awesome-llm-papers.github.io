---
layout: publication
title: Contrastive Chain-of-thought Prompting
authors: Yew Ken Chia, Guizhen Chen, Luu Anh Tuan, Soujanya Poria, Lidong Bing
conference: No Venue
year: 2023
bibkey: chia2023contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.09277'}]
tags: ["Prompting"]
short_authors: Chia et al.
---
Despite the success of chain of thought in enhancing language model reasoning, the underlying process remains less well understood. Although logically sound reasoning appears inherently crucial for chain of thought, prior studies surprisingly reveal minimal impact when using invalid demonstrations instead. Furthermore, the conventional chain of thought does not inform language models on what mistakes to avoid, which potentially leads to more errors. Hence, inspired by how humans can learn from both positive and negative examples, we propose contrastive chain of thought to enhance language model reasoning. Compared to the conventional chain of thought, our approach provides both valid and invalid reasoning demonstrations, to guide the model to reason step-by-step while reducing reasoning mistakes. To improve generalization, we introduce an automatic method to construct contrastive demonstrations. Our experiments on reasoning benchmarks demonstrate that contrastive chain of thought can serve as a general enhancement of chain-of-thought prompting.

https://huggingface.co/discussions/paper/6556de848076124b8d7fbce1