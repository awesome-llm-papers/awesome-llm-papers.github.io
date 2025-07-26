---
layout: publication
title: Chain-of-model Learning For Language Model
authors: Kaitao Song, Xiaohua Wang, Xu Tan, Huiqiang Jiang, Chengruidong Zhang, Yongliang
  Shen, Cen Lu, Zihao Li, Zifan Song, Caihua Shan, Yansen Wang, Kan Ren, Xiaoqing
  Zheng, Tao Qin, Yuqing Yang, Dongsheng Li, Lili Qiu
conference: No Venue
year: 2025
bibkey: song2025chain
additional_links: [{name: Code, url: 'https://github.com/microsoft/CoLM'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682bf77afdfa3c5de0eb1e50'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.11820'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Song et al.
---
In this paper, we propose a novel learning paradigm, termed Chain-of-Model (CoM), which incorporates the causal relationship into the hidden states of each layer as a chain style, thereby introducing great scaling efficiency in model training and inference flexibility in deployment. We introduce the concept of Chain-of-Representation (CoR), which formulates the hidden states at each layer as a combination of multiple sub-representations (i.e., chains) at the hidden dimension level. In each layer, each chain from the output representations can only view all of its preceding chains in the input representations. Consequently, the model built upon CoM framework can progressively scale up the model size by increasing the chains based on the previous models (i.e., chains), and offer multiple sub-models at varying sizes for elastic inference by using different chain numbers. Based on this principle, we devise Chain-of-Language-Model (CoLM), which incorporates the idea of CoM into each layer of Transformer architecture. Based on CoLM, we further introduce CoLM-Air by introducing a KV sharing mechanism, that computes all keys and values within the first chain and then shares across all chains. This design demonstrates additional extensibility, such as enabling seamless LM switching, prefilling acceleration and so on. Experimental results demonstrate our CoLM family can achieve comparable performance to the standard Transformer, while simultaneously enabling greater flexiblity, such as progressive scaling to improve training efficiency and offer multiple varying model sizes for elastic inference, paving a a new way toward building language models. Our code will be released in the future at: https://github.com/microsoft/CoLM.

https://huggingface.co/discussions/paper/682bf77afdfa3c5de0eb1e50