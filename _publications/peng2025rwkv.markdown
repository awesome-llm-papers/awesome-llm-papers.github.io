---
layout: publication
title: RWKV-7 "goose" With Expressive Dynamic State Evolution
authors: Bo Peng, Ruichong Zhang, Daniel Goldstein, Eric Alcaide, Haowen Hou, Janna
  Lu, William Merrill, Guangyu Song, Kaifeng Tan, Saiteja Utpala, Nathan Wilce, Johan
  S. Wind, Tianyi Wu, Daniel Wuttke, Christian Zhou-zheng
conference: No Venue
year: 2025
bibkey: peng2025rwkv
additional_links: [{name: Code, url: 'https://huggingface.co/RWKV,'}, {name: Code,
    url: 'https://github.com/RWKV/RWKV-LM'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67da21ee78c08b432f9fee71'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.14456'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Peng et al.
---
We present RWKV-7 "Goose", a new sequence modeling architecture, along with pre-trained language models that establish a new state-of-the-art in downstream performance at the 3 billion parameter scale on multilingual tasks, and match current SoTA English language performance despite being trained on dramatically fewer tokens than other top 3B models. Nevertheless, RWKV-7 models require only constant memory usage and constant inference time per token. RWKV-7 introduces a newly generalized formulation of the delta rule with vector-valued gating and in-context learning rates, as well as a relaxed value replacement rule. We show that RWKV-7 can perform state tracking and recognize all regular languages, while retaining parallelizability of training. This exceeds the capabilities of Transformers under standard complexity conjectures, which are limited to TC^0. To demonstrate RWKV-7's language modeling capability, we also present an extended open source 3.1 trillion token multilingual corpus, and train four RWKV-7 models ranging from 0.19 billion to 2.9 billion parameters on this dataset. To foster openness, reproduction, and adoption, we release our models and dataset component listing at https://huggingface.co/RWKV, and our training and inference code at https://github.com/RWKV/RWKV-LM all under the Apache 2.0 License.

https://huggingface.co/discussions/paper/67da21ee78c08b432f9fee71