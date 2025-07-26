---
layout: publication
title: 'Robustft: Robust Supervised Fine-tuning For Large Language Models Under Noisy
  Response'
authors: Junyu Luo, Xiao Luo, Kaize Ding, Jingyang Yuan, Zhiping Xiao, Ming Zhang
conference: No Venue
year: 2024
bibkey: luo2024robustft
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.14922'}]
tags: ["Fine-Tuning"]
short_authors: Luo et al.
---
Supervised fine-tuning (SFT) plays a crucial role in adapting large language models (LLMs) to specific domains or tasks. However, as demonstrated by empirical experiments, the collected data inevitably contains noise in practical applications, which poses significant challenges to model performance on downstream tasks. Therefore, there is an urgent need for a noise-robust SFT framework to enhance model capabilities in downstream tasks. To address this challenge, we introduce a robust SFT framework (RobustFT) that performs noise detection and relabeling on downstream task data. For noise identification, our approach employs a multi-expert collaborative system with inference-enhanced models to achieve superior noise detection. In the denoising phase, we utilize a context-enhanced strategy, which incorporates the most relevant and confident knowledge followed by careful assessment to generate reliable annotations. Additionally, we introduce an effective data selection mechanism based on response entropy, ensuring only high-quality samples are retained for fine-tuning. Extensive experiments conducted on multiple LLMs across five datasets demonstrate RobustFT's exceptional performance in noisy scenarios.

https://huggingface.co/discussions/paper/676a2354463437b5e1217e51