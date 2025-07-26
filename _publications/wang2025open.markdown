---
layout: publication
title: 'Open-qwen2vl: Compute-efficient Pre-training Of Fully-open Multimodal Llms
  On Academic Resources'
authors: Weizhi Wang, Yu Tian, Linjie Yang, Heng Wang, Xifeng Yan
conference: No Venue
year: 2025
bibkey: wang2025open
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ecaf546560da48c5c341dc'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.00595'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Wang et al.
---
The reproduction of state-of-the-art multimodal LLM pre-training faces barriers at every stage of the pipeline, including high-quality data filtering, multimodal data mixture strategies, sequence packing techniques, and training frameworks. We introduce Open-Qwen2VL, a fully open-source 2B-parameter Multimodal Large Language Model pre-trained efficiently on 29M image-text pairs using only 442 A100-40G GPU hours. Our approach employs low-to-high dynamic image resolution and multimodal sequence packing to significantly enhance pre-training efficiency. The training dataset was carefully curated using both MLLM-based filtering techniques (e.g., MLM-Filter) and conventional CLIP-based filtering methods, substantially improving data quality and training efficiency. The Open-Qwen2VL pre-training is conducted on academic level 8xA100-40G GPUs at UCSB on 5B packed multimodal tokens, which is 0.36% of 1.4T multimodal pre-training tokens of Qwen2-VL. The final instruction-tuned Open-Qwen2VL outperforms partially-open state-of-the-art MLLM Qwen2-VL-2B on various multimodal benchmarks of MMBench, SEEDBench, MMstar, and MathVista, indicating the remarkable training efficiency of Open-Qwen2VL. We open-source all aspects of our work, including compute-efficient and data-efficient training details, data filtering methods, sequence packing scripts, pre-training data in WebDataset format, FSDP-based training codebase, and both base and instruction-tuned model checkpoints. We redefine "fully open" for multimodal LLMs as the complete release of: 1) the training codebase, 2) detailed data filtering techniques, and 3) all pre-training and supervised fine-tuning data used to develop the model.

https://huggingface.co/discussions/paper/67ecaf546560da48c5c341dc