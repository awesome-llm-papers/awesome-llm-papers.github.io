---
layout: publication
title: 'LM2: Large Memory Models'
authors: Jikun Kang, Wenqi Wu, Filippos Christianos, Alex J. Chan, Fraser Greenlee,
  George Thomas, Marvin Purtorab, Andy Toulis
conference: No Venue
year: 2025
bibkey: kang2025lm2
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67aac01dd7b18841e7c26739'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.06049'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Kang et al.
---
This paper introduces the Large Memory Model (LM2), a decoder-only Transformer architecture enhanced with an auxiliary memory module that aims to address the limitations of standard Transformers in multi-step reasoning, relational argumentation, and synthesizing information distributed over long contexts. The proposed LM2 incorporates a memory module that acts as a contextual representation repository, interacting with input tokens via cross attention and updating through gating mechanisms. To preserve the Transformers general-purpose capabilities, LM2 maintains the original information flow while integrating a complementary memory pathway. Experimental results on the BABILong benchmark demonstrate that the LM2model outperforms both the memory-augmented RMT model by 37.1% and the baseline Llama-3.2 model by 86.3% on average across tasks. LM2 exhibits exceptional capabilities in multi-hop inference, numerical reasoning, and large-context question-answering. On the MMLU dataset, it achieves a 5.0% improvement over a pre-trained vanilla model, demonstrating that its memory module does not degrade performance on general tasks. Further, in our analysis, we explore the memory interpretability, effectiveness of memory modules, and test-time behavior. Our findings emphasize the importance of explicit memory in enhancing Transformer architectures.

https://huggingface.co/discussions/paper/67aac01dd7b18841e7c26739