---
layout: publication
title: 'Baichuanseed: Sharing The Potential Of Extensive Data Collection And Deduplication
  By Introducing A Competitive Large Language Model Baseline'
authors: Guosheng Dong, da Pan, Yiding Sun, Shusen Zhang, Zheng Liang, Xin Wu, Yanjun
  Shen, Fan Yang, Haoze Sun, Tianpeng Li, Mingan Lin, Jianhua Xu, Yufan Zhang, Xiaonan
  Nie, Lei Su, Bingning Wang, Wentao Zhang, Jiaxin Mao, Zenan Zhou, Weipeng Chen
conference: No Venue
year: 2024
bibkey: dong2024baichuanseed
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.15079'}]
tags: ["Datasets"]
short_authors: Dong et al.
---
The general capabilities of Large Language Models (LLM) highly rely on the composition and selection on extensive pretraining datasets, treated as commercial secrets by several institutions. To mitigate this issue, we open-source the details of a universally applicable data processing pipeline and validate its effectiveness and potential by introducing a competitive LLM baseline. Specifically, the data processing pipeline consists of broad collection to scale up and reweighting to improve quality. We then pretrain a 7B model BaichuanSEED with 3T tokens processed by our pipeline without any deliberate downstream task-related optimization, followed by an easy but effective supervised fine-tuning stage. BaichuanSEED demonstrates consistency and predictability throughout training and achieves comparable performance on comprehensive benchmarks with several commercial advanced large language models, such as Qwen1.5 and Llama3. We also conduct several heuristic experiments to discuss the potential for further optimization of downstream tasks, such as mathematics and coding.

https://huggingface.co/discussions/paper/66d008cbf1e57767fdf55bef