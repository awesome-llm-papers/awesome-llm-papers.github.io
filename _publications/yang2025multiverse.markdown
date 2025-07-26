---
layout: publication
title: 'Multiverse: Your Language Models Secretly Decide How To Parallelize And Merge
  Generation'
authors: Xinyu Yang, Yuwei An, Hongyi Liu, Tianqi Chen, Beidi Chen
conference: No Venue
year: 2025
bibkey: yang2025multiverse
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.09991'}]
tags: ["Efficiency", "Evaluation", "Fine-Tuning", "Memory & Context", "Tools", "Training Techniques"]
short_authors: Yang et al.
---
Autoregressive Large Language Models (AR-LLMs) frequently exhibit implicit parallelism in sequential generation. Inspired by this, we introduce Multiverse, a new generative model that enables natively parallel generation. Multiverse internalizes a MapReduce paradigm, generating automatically through three stages: (i) a Map stage for adaptive task decomposition, (ii) a Process stage for parallel subtask execution, and (iii) a Reduce stage for lossless result synthesis. Next, we build a real-world Multiverse reasoning model with co-design of data, algorithm, and system, enabling rapid and seamless transfer from frontier AR-LLMs. Starting from sequential reasoning chains, we create Multiverse 1K by converting them into structured training data using an automated LLM-assisted pipeline, avoiding costly human annotations. Algorithmically, we design Multiverse Attention to separate parallel reasoning steps while keeping compatibility with causal attention for efficient training. Systematically, we implement Multiverse Engine to enable parallel inference. It features a dedicated scheduler that dynamically switches between sequential and parallel generation, triggered directly by the model. After a 3-hour fine-tuning with 1K examples, our Multiverse-32B stands as the only open-sourced non-AR model achieving performance on par with leading AR-LLMs of the same scale, evidenced by AIME24 & 25 scores of 54% and 46%, respectively. Moreover, our budget control experiments show that Multiverse-32B exhibits superior scaling, outperforming AR-LLMs by 1.87% on average using the same context length. Such scaling further leads to practical efficiency gain, achieving up to 2x speedup across varying batch sizes. We have open-sourced the entire Multiverse ecosystem, including data, model weights, engine, supporting tools, as well as complete data curation prompts and detailed training and evaluation recipes.

https://huggingface.co/discussions/paper/684adf26dbd21a9cc27b0ecd