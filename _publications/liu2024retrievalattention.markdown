---
layout: publication
title: 'Retrievalattention: Accelerating Long-context LLM Inference Via Vector Retrieval'
authors: di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang,
  Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing
  Yang, Lili Qiu
conference: No Venue
year: 2024
bibkey: liu2024retrievalattention
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.10516'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Transformer-based large Language Models (LLMs) become increasingly important in various domains. However, the quadratic time complexity of attention operation poses a significant challenge for scaling to longer contexts due to the extremely high inference latency and GPU memory consumption for caching key-value (KV) vectors. This paper proposes RetrievalAttention, a training-free approach to accelerate attention computation. To leverage the dynamic sparse property of attention, RetrievalAttention builds approximate nearest neighbor search (ANNS) indexes upon KV vectors in CPU memory and retrieves the most relevant ones via vector search during generation. Due to the out-of-distribution (OOD) between query vectors and key vectors, off-the-shelf ANNS indexes still need to scan O(N) (usually 30% of all keys) data for accurate retrieval, which fails to exploit the high sparsity. RetrievalAttention first identifies the OOD challenge of ANNS-based attention, and addresses it via an attention-aware vector search algorithm that can adapt to queries and only access 1--3% of data, thus achieving a sub-linear time complexity. RetrievalAttention greatly reduces the inference cost of long-context LLM with much lower GPU memory requirements while maintaining the model accuracy. Especially, RetrievalAttention only needs 16GB GPU memory for serving 128K tokens in LLMs with 8B parameters, which is capable of generating one token in 0.188 seconds on a single NVIDIA RTX4090 (24GB).

https://huggingface.co/discussions/paper/66e8f30e6646c8f0e8b11e00