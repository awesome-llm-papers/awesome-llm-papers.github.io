---
layout: publication
title: 'Multifinben: A Multilingual, Multimodal, And Difficulty-aware Benchmark For
  Financial LLM Evaluation'
authors: Xueqing Peng, Lingfei Qian, Yan Wang, Ruoyu Xiang, Yueru He, Yang Ren, Mingyang
  Jiang, Jeff Zhao, Huan He, Yi Han, Yun Feng, Yuechen Jiang, Yupeng Cao, Haohang
  Li, Yangyang Yu, Xiaoyu Wang, Penglei Gao, Shengyuan Lin, Keyi Wang, Shanshan Yang,
  Yilun Zhao, Zhiwei Liu, Peng Lu, Jerry Huang, Suyuchen Wang, Triantafillos Papadopoulos,
  Polydoros Giannouris, Efstathia Soufleri, Nuo Chen, Guojun Xiong, Zhiyang Deng,
  Yijia Zhao, Mingquan Lin, Meikang Qiu, Kaleb E Smith, Arman Cohan, Xiao-yang Liu,
  Jimin Huang, Alejandro Lopez-lira, Xi Chen, Junichi Tsujii, Jian-yun Nie, Sophia
  Ananiadou, Qianqian Xie
conference: No Venue
year: 2025
bibkey: peng2025multifinben
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.14028'}]
tags: ["Datasets", "Evaluation"]
short_authors: Peng et al.
---
Recent advances in large language models (LLMs) have accelerated progress in financial NLP and applications, yet existing benchmarks remain limited to monolingual and unimodal settings, often over-relying on simple tasks and failing to reflect the complexity of real-world financial communication. We introduce MultiFinBen, the first multilingual and multimodal benchmark tailored to the global financial domain, evaluating LLMs across modalities (text, vision, audio) and linguistic settings (monolingual, bilingual, multilingual) on domain-specific tasks. We introduce two novel tasks, including PolyFiQA-Easy and PolyFiQA-Expert, the first multilingual financial benchmarks requiring models to perform complex reasoning over mixed-language inputs; and EnglishOCR and SpanishOCR, the first OCR-embedded financial QA tasks challenging models to extract and reason over information from visual-text financial documents. Moreover, we propose a dynamic, difficulty-aware selection mechanism and curate a compact, balanced benchmark rather than simple aggregation existing datasets. Extensive evaluation of 22 state-of-the-art models reveals that even the strongest models, despite their general multimodal and multilingual capabilities, struggle dramatically when faced with complex cross-lingual and multimodal tasks in financial domain. MultiFinBen is publicly released to foster transparent, reproducible, and inclusive progress in financial studies and applications.

https://huggingface.co/discussions/paper/685240ab0164cd1316710596