---
layout: publication
title: Simple And Scalable Strategies To Continually Pre-train Large Language Models
authors: "Adam Ibrahim, Benjamin Th\xE9rien, Kshitij Gupta, Mats L. Richter, Quentin\
  \ Anthony, Timoth\xE9e Lesort, Eugene Belilovsky, Irina Rish"
conference: No Venue
year: 2024
bibkey: ibrahim2024simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.08763'}]
tags: ["Training Techniques"]
short_authors: Ibrahim et al.
---
Large language models (LLMs) are routinely pre-trained on billions of tokens, only to start the process over again once new data becomes available. A much more efficient solution is to continually pre-train these models, saving significant compute compared to re-training. However, the distribution shift induced by new data typically results in degraded performance on previous data or poor adaptation to the new data. In this work, we show that a simple and scalable combination of learning rate (LR) re-warming, LR re-decaying, and replay of previous data is sufficient to match the performance of fully re-training from scratch on all available data, as measured by final loss and language model (LM) evaluation benchmarks. Specifically, we show this for a weak but realistic distribution shift between two commonly used LLM pre-training datasets (EnglishrightarrowEnglish) and a stronger distribution shift (EnglishrightarrowGerman) at the 405M parameter model scale with large dataset sizes (hundreds of billions of tokens). Selecting the weak but realistic shift for larger-scale experiments, we also find that our continual learning strategies match the re-training baseline for a 10B parameter LLM. Our results demonstrate that LLMs can be successfully updated via simple and scalable continual learning strategies, matching the re-training baseline using only a fraction of the compute. Finally, inspired by previous work, we propose alternatives to the cosine learning rate schedule that help circumvent forgetting induced by LR re-warming and that are not bound to a fixed token budget.

https://huggingface.co/discussions/paper/65f271e4b06ca1ff48a13106