---
layout: publication
title: 'Retentive Network: A Successor To Transformer For Large Language Models'
authors: Yutao Sun, Li Dong, Shaohan Huang, Shuming Ma, Yuqing Xia, Jilong Xue, Jianyong
  Wang, Furu Wei
conference: No Venue
year: 2023
bibkey: sun2023retentive
additional_links: [{name: Code, url: 'https://aka.ms/retnet'}, {name: Code, url: 'https://huggingface.co/discussions/paper/64b5fb597d9d8f9970f9f7f1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.08621'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Sun et al.
---
In this work, we propose Retentive Network (RetNet) as a foundation architecture for large language models, simultaneously achieving training parallelism, low-cost inference, and good performance. We theoretically derive the connection between recurrence and attention. Then we propose the retention mechanism for sequence modeling, which supports three computation paradigms, i.e., parallel, recurrent, and chunkwise recurrent. Specifically, the parallel representation allows for training parallelism. The recurrent representation enables low-cost O(1) inference, which improves decoding throughput, latency, and GPU memory without sacrificing performance. The chunkwise recurrent representation facilitates efficient long-sequence modeling with linear complexity, where each chunk is encoded parallelly while recurrently summarizing the chunks. Experimental results on language modeling show that RetNet achieves favorable scaling results, parallel training, low-cost deployment, and efficient inference. The intriguing properties make RetNet a strong successor to Transformer for large language models. Code will be available at https://aka.ms/retnet.

https://huggingface.co/discussions/paper/64b5fb597d9d8f9970f9f7f1