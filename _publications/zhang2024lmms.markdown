---
layout: publication
title: 'Lmms-eval: Reality Check On The Evaluation Of Large Multimodal Models'
authors: Kaichen Zhang, Bo Li, Peiyuan Zhang, Fanyi Pu, Joshua Adrian Cahyono, Kairui
  Hu, Shuai Liu, Yuanhan Zhang, Jingkang Yang, Chunyuan Li, Ziwei Liu
conference: No Venue
year: 2024
bibkey: zhang2024lmms
additional_links: [{name: Code, url: 'https://github.com/EvolvingLMMs-Lab/lmms-eval'},
  {name: Code, url: 'https://huggingface.co/spaces/lmms-lab/LiveBench'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66987d98a029d7f9e39daac2'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2407.12772'}]
tags: ["Evaluation", "Tools"]
short_authors: Zhang et al.
---
The advances of large foundation models necessitate wide-coverage, low-cost, and zero-contamination benchmarks. Despite continuous exploration of language model evaluations, comprehensive studies on the evaluation of Large Multi-modal Models (LMMs) remain limited. In this work, we introduce LMMS-EVAL, a unified and standardized multimodal benchmark framework with over 50 tasks and more than 10 models to promote transparent and reproducible evaluations. Although LMMS-EVAL offers comprehensive coverage, we find it still falls short in achieving low cost and zero contamination. To approach this evaluation trilemma, we further introduce LMMS-EVAL LITE, a pruned evaluation toolkit that emphasizes both coverage and efficiency. Additionally, we present Multimodal LIVEBENCH that utilizes continuously updating news and online forums to assess models' generalization abilities in the wild, featuring a low-cost and zero-contamination evaluation approach. In summary, our work highlights the importance of considering the evaluation trilemma and provides practical solutions to navigate the trade-offs in evaluating large multi-modal models, paving the way for more effective and reliable benchmarking of LMMs. We opensource our codebase and maintain leaderboard of LIVEBENCH at https://github.com/EvolvingLMMs-Lab/lmms-eval and https://huggingface.co/spaces/lmms-lab/LiveBench.

https://huggingface.co/discussions/paper/66987d98a029d7f9e39daac2