---
layout: publication
title: 'Slimgpt: Layer-wise Structured Pruning For Large Language Models'
authors: Ling et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: ling2024slimgpt
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.18110'}]
tags: [EMNLP, Attention Mechanism, GPT, Tools, Evaluation, Model Architecture, Efficiency
    And Optimization, Pruning, Datasets]
---
Large language models (LLMs) have garnered significant attention for their
remarkable capabilities across various domains, whose vast parameter scales
present challenges for practical deployment. Structured pruning is an effective
method to balance model performance with efficiency, but performance
restoration under computational resource constraints is a principal challenge
in pruning LLMs. Therefore, we present a low-cost and fast structured pruning
method for LLMs named SlimGPT based on the Optimal Brain Surgeon framework. We
propose Batched Greedy Pruning for rapid and near-optimal pruning, which
enhances the accuracy of head-wise pruning error estimation through grouped
Cholesky decomposition and improves the pruning efficiency of FFN via Dynamic
Group Size, thereby achieving approximate local optimal pruning results within
one hour. Besides, we explore the limitations of layer-wise pruning from the
perspective of error accumulation and propose Incremental Pruning Ratio, a
non-uniform pruning strategy to reduce performance degradation. Experimental
results on the LLaMA benchmark show that SlimGPT outperforms other methods and
achieves state-of-the-art results.