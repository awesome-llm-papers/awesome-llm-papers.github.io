---
layout: publication
title: Deciphering Cross-modal Alignment In Large Vision-language Models With Modality
  Integration Rate
authors: Qidong Huang, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Jiaqi Wang,
  Dahua Lin, Weiming Zhang, Nenghai Yu
conference: No Venue
year: 2024
bibkey: huang2024deciphering
additional_links: [{name: Code, url: 'https://github.com/shikiw/Modality-Integration-Rate'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/670748dc49d08fabeb1ae632'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.07167'}]
tags: ["Model Architecture"]
short_authors: Huang et al.
---
We present the Modality Integration Rate (MIR), an effective, robust, and generalized metric to indicate the multi-modal pre-training quality of Large Vision Language Models (LVLMs). Large-scale pre-training plays a critical role in building capable LVLMs, while evaluating its training quality without the costly supervised fine-tuning stage is under-explored. Loss, perplexity, and in-context evaluation results are commonly used pre-training metrics for Large Language Models (LLMs), while we observed that these metrics are less indicative when aligning a well-trained LLM with a new modality. Due to the lack of proper metrics, the research of LVLMs in the critical pre-training stage is hindered greatly, including the training data choice, efficient module design, etc. In this paper, we propose evaluating the pre-training quality from the inter-modal distribution distance perspective and present MIR, the Modality Integration Rate, which is 1) Effective to represent the pre-training quality and show a positive relation with the benchmark performance after supervised fine-tuning. 2) Robust toward different training/evaluation data. 3) Generalize across training configurations and architecture choices. We conduct a series of pre-training experiments to explore the effectiveness of MIR and observe satisfactory results that MIR is indicative about training data selection, training strategy schedule, and model architecture design to get better pre-training results. We hope MIR could be a helpful metric for building capable LVLMs and inspire the following research about modality alignment in different areas. Our code is at: https://github.com/shikiw/Modality-Integration-Rate.

https://huggingface.co/discussions/paper/670748dc49d08fabeb1ae632