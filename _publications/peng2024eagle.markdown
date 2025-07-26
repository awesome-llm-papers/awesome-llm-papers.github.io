---
layout: publication
title: 'Eagle And Finch: RWKV With Matrix-valued States And Dynamic Recurrence'
authors: "Bo Peng, Daniel Goldstein, Quentin Anthony, Alon Albalak, Eric Alcaide,\
  \ Stella Biderman, Eugene Cheah, Teddy Ferdinan, Haowen Hou, Przemys\u0142aw Kazienko,\
  \ Kranthi Kiran Gv, Jan Koco\u0144, Bart\u0142omiej Koptyra, Satyapriya Krishna,\
  \ Ronald Mcclelland Jr., Niklas Muennighoff, Fares Obeid, Atsushi Saito, Guangyu\
  \ Song, Haoqin Tu, Stanis\u0142aw Wo\u017Aniak, Ruichong Zhang, Bingchen Zhao, Qihang\
  \ Zhao, Peng Zhou, Jian Zhu, Rui-jie Zhu"
conference: No Venue
year: 2024
bibkey: peng2024eagle
additional_links: [{name: Code, url: 'https://huggingface.co/RWKV'}, {name: Code,
    url: 'https://github.com/RWKV/RWKV-LM'}, {name: Code, url: 'https://github.com/RWKV/ChatRWKV'},
  {name: Code, url: 'https://github.com/RWKV/RWKV-infctx-trainer'}, {name: Code, url: 'https://huggingface.co/discussions/paper/6615f99b24c94fd8a2231242'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.05892'}]
tags: ["Model Architecture"]
short_authors: Peng et al.
---
We present Eagle (RWKV-5) and Finch (RWKV-6), sequence models improving upon the RWKV (RWKV-4) architecture. Our architectural design advancements include multi-headed matrix-valued states and a dynamic recurrence mechanism that improve expressivity while maintaining the inference efficiency characteristics of RNNs. We introduce a new multilingual corpus with 1.12 trillion tokens and a fast tokenizer based on greedy matching for enhanced multilinguality. We trained four Eagle models, ranging from 0.46 to 7.5 billion parameters, and two Finch models with 1.6 and 3.1 billion parameters and find that they achieve competitive performance across a wide variety of benchmarks. We release all our models on HuggingFace under the Apache 2.0 license. Models at: https://huggingface.co/RWKV Training code at: https://github.com/RWKV/RWKV-LM Inference code at: https://github.com/RWKV/ChatRWKV Time-parallel training code at: https://github.com/RWKV/RWKV-infctx-trainer

https://huggingface.co/discussions/paper/6615f99b24c94fd8a2231242