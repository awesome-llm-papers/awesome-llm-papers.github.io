---
layout: publication
title: 'Lm-infinite: Simple On-the-fly Length Generalization For Large Language Models'
authors: Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang
conference: No Venue
year: 2023
bibkey: han2023lm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2308.16137'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Han et al.
---
In recent years, there have been remarkable advancements in the performance of Transformer-based Large Language Models (LLMs) across various domains. As these LLMs are deployed for increasingly complex tasks, they often face the needs to conduct longer reasoning processes or understanding larger contexts. In these situations, the length generalization failure of LLMs on long sequences become more prominent. Most pre-training schemes truncate training sequences to a fixed length (such as 2048 for LLaMa). LLMs often struggle to generate fluent texts, let alone carry out downstream tasks, after longer contexts, even with relative positional encoding which is designed to cope with this problem. Common solutions such as finetuning on longer corpora often involves daunting hardware and time costs and requires careful training process design. To more efficiently leverage the generation capacity of existing LLMs, we theoretically and empirically investigate the main out-of-distribution (OOD) factors contributing to this problem. Inspired by this diagnosis, we propose a simple yet effective solution for on-the-fly length generalization, LM-Infinite, which involves only a Lambda-shaped attention mask and a distance limit while requiring no parameter updates or learning. We find it applicable to a variety of LLMs using relative-position encoding methods. LM-Infinite is computational efficient with O(n) time and space, and demonstrates consistent fluency and generation quality to as long as 32k tokens on ArXiv and OpenWebText2 datasets, with 2.72x decoding speedup. On downstream task such as passkey retrieval, it continues to work on inputs much longer than training lengths where vanilla models fail immediately.

https://huggingface.co/discussions/paper/64f0078050dae59768e5bdb3