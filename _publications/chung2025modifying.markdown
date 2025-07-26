---
layout: publication
title: Modifying Large Language Model Post-training For Diverse Creative Writing
authors: John Joon Young Chung, Vishakh Padmakumar, Melissa Roemmele, Yuqian Sun,
  Max Kreminski
conference: No Venue
year: 2025
bibkey: chung2025modifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.17126'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Chung et al.
---
As creative writing tasks do not have singular correct answers, large language models (LLMs) trained to perform these tasks should be able to generate diverse valid outputs. However, LLM post-training often focuses on improving generation quality but neglects to facilitate output diversity. Hence, in creative writing generation, we investigate post-training approaches to promote both output diversity and quality. Our core idea is to include deviation -- the degree of difference between a training sample and all other samples with the same prompt -- in the training objective to facilitate learning from rare high-quality instances. By adopting our approach to direct preference optimization (DPO) and odds ratio preference optimization (ORPO), we demonstrate that we can promote the output diversity of trained models while minimally decreasing quality. Our best model with 8B parameters could achieve on-par diversity as a human-created dataset while having output quality similar to the best instruction-tuned models we examined, GPT-4o and DeepSeek-R1. We further validate our approaches with a human evaluation, an ablation, and a comparison to an existing diversification approach, DivPO.

https://huggingface.co/discussions/paper/67e0beb574fc794321fb4b04