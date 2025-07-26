---
layout: publication
title: 'Weblinx: Real-world Website Navigation With Multi-turn Dialogue'
authors: "Xing Han L\xF9, Zden\u011Bk Kasner, Siva Reddy"
conference: No Venue
year: 2024
bibkey: "l\xF92024weblinx"
additional_links: [{name: Code, url: 'https://mcgill-nlp.github.io/weblinx'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/65c59242ed68e7aafdc5cb29'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2402.05930'}]
tags: []
short_authors: "Xing Han L\xF9, Zden\u011Bk Kasner, Siva Reddy"
---
We propose the problem of conversational web navigation, where a digital agent controls a web browser and follows user instructions to solve real-world tasks in a multi-turn dialogue fashion. To support this problem, we introduce WEBLINX - a large-scale benchmark of 100K interactions across 2300 expert demonstrations of conversational web navigation. Our benchmark covers a broad range of patterns on over 150 real-world websites and can be used to train and evaluate agents in diverse scenarios. Due to the magnitude of information present, Large Language Models (LLMs) cannot process entire web pages in real-time. To solve this bottleneck, we design a retrieval-inspired model that efficiently prunes HTML pages by ranking relevant elements. We use the selected elements, along with screenshots and action history, to assess a variety of models for their ability to replicate human behavior when navigating the web. Our experiments span from small text-only to proprietary multimodal LLMs. We find that smaller finetuned decoders surpass the best zero-shot LLMs (including GPT-4V), but also larger finetuned multimodal models which were explicitly pretrained on screenshots. However, all finetuned models struggle to generalize to unseen websites. Our findings highlight the need for large multimodal models that can generalize to novel settings. Our code, data and models are available for research: https://mcgill-nlp.github.io/weblinx

https://huggingface.co/discussions/paper/65c59242ed68e7aafdc5cb29