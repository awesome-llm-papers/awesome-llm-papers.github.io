---
layout: publication
title: 'Seakr: Self-aware Knowledge Retrieval For Adaptive Retrieval Augmented Generation'
authors: Zijun Yao, Weijian Qi, Liangming Pan, Shulin Cao, Linmei Hu, Weichuan Liu,
  Lei Hou, Juanzi Li
conference: No Venue
year: 2024
bibkey: yao2024seakr
additional_links: [{name: Code, url: 'https://github.com/THU-KEG/SeaKR'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/667e1f62e677941031fd7e5d'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2406.19215'}]
tags: ["Has Code", "RAG"]
short_authors: Yao et al.
---
This paper introduces Self-aware Knowledge Retrieval (SeaKR), a novel adaptive RAG model that extracts self-aware uncertainty of LLMs from their internal states. SeaKR activates retrieval when the LLMs present high self-aware uncertainty for generation. To effectively integrate retrieved knowledge snippets, SeaKR re-ranks them based on LLM's self-aware uncertainty to preserve the snippet that reduces their uncertainty to the utmost. To facilitate solving complex tasks that require multiple retrievals, SeaKR utilizes their self-aware uncertainty to choose among different reasoning strategies. Our experiments on both complex and simple Question Answering datasets show that SeaKR outperforms existing adaptive RAG methods. We release our code at https://github.com/THU-KEG/SeaKR.

https://huggingface.co/discussions/paper/667e1f62e677941031fd7e5d