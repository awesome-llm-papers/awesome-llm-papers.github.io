---
layout: publication
title: 'The Mamba In The Llama: Distilling And Accelerating Hybrid Models'
authors: Junxiong Wang, Daniele Paliotta, Avner May, Alexander M. Rush, Tri Dao
conference: No Venue
year: 2024
bibkey: wang2024mamba
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.15237'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
Linear RNN architectures, like Mamba, can be competitive with Transformer models in language modeling while having advantageous deployment characteristics. Given the focus on training large-scale Transformer models, we consider the challenge of converting these pretrained models for deployment. We demonstrate that it is feasible to distill large Transformers into linear RNNs by reusing the linear projection weights from attention layers with academic GPU resources. The resulting hybrid model, which incorporates a quarter of the attention layers, achieves performance comparable to the original Transformer in chat benchmarks and outperforms open-source hybrid Mamba models trained from scratch with trillions of tokens in both chat benchmarks and general benchmarks. Moreover, we introduce a hardware-aware speculative decoding algorithm that accelerates the inference speed of Mamba and hybrid models. Overall we show how, with limited computation resources, we can remove many of the original attention layers and generate from the resulting model more efficiently. Our top-performing model, distilled from Llama3-8B-Instruct, achieves a 29.61 length-controlled win rate on AlpacaEval 2 against GPT-4 and 7.35 on MT-Bench, surpassing the best instruction-tuned linear RNN model.

https://huggingface.co/discussions/paper/66ce96309ca851092d9355a2