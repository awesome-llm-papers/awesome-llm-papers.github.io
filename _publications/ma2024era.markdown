---
layout: publication
title: 'The Era Of 1-bit Llms: All Large Language Models Are In 1.58 Bits'
authors: Shuming Ma, Hongyu Wang, Lingxiao Ma, Lei Wang, Wenhui Wang, Shaohan Huang,
  Li Dong, Ruiping Wang, Jilong Xue, Furu Wei
conference: No Venue
year: 2024
bibkey: ma2024era
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.17764'}]
tags: ["Model Architecture"]
short_authors: Ma et al.
---
Recent research, such as BitNet, is paving the way for a new era of 1-bit Large Language Models (LLMs). In this work, we introduce a 1-bit LLM variant, namely BitNet b1.58, in which every single parameter (or weight) of the LLM is ternary \{-1, 0, 1\}. It matches the full-precision (i.e., FP16 or BF16) Transformer LLM with the same model size and training tokens in terms of both perplexity and end-task performance, while being significantly more cost-effective in terms of latency, memory, throughput, and energy consumption. More profoundly, the 1.58-bit LLM defines a new scaling law and recipe for training new generations of LLMs that are both high-performance and cost-effective. Furthermore, it enables a new computation paradigm and opens the door for designing specific hardware optimized for 1-bit LLMs.

https://huggingface.co/discussions/paper/65ded50033599459308af393