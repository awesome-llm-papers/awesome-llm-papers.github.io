---
layout: publication
title: Are Your Llms Capable Of Stable Reasoning?
authors: Junnan Liu, Hongwei Liu, Linchen Xiao, Ziyi Wang, Kuikun Liu, Songyang Gao,
  Wenwei Zhang, Songyang Zhang, Kai Chen
conference: No Venue
year: 2024
bibkey: liu2024are
additional_links: [{name: Code, url: 'https://github.com/open-compass/GPassK'}, {
    name: Paper, url: 'https://arxiv.org/abs/hf2412.13147'}]
tags: ["Applications", "Evaluation", "Has Code"]
short_authors: Liu et al.
---
The rapid advancement of Large Language Models (LLMs) has demonstrated remarkable progress in complex reasoning tasks. However, a significant discrepancy persists between benchmark performances and real-world applications. We identify this gap as primarily stemming from current evaluation protocols and metrics, which inadequately capture the full spectrum of LLM capabilities, particularly in complex reasoning tasks where both accuracy and consistency are crucial. This work makes two key contributions. First, we introduce G-Pass@k, a novel evaluation metric that provides a continuous assessment of model performance across multiple sampling attempts, quantifying both the model's peak performance potential and its stability. Second, we present LiveMathBench, a dynamic benchmark comprising challenging, contemporary mathematical problems designed to minimize data leakage risks during evaluation. Through extensive experiments using G-Pass@k on state-of-the-art LLMs with LiveMathBench, we provide comprehensive insights into both their maximum capabilities and operational consistency. Our findings reveal substantial room for improvement in LLMs' "realistic" reasoning capabilities, highlighting the need for more robust evaluation methods. The benchmark and detailed results are available at: https://github.com/open-compass/GPassK.

https://huggingface.co/discussions/paper/67623bb9d44ba09e9119fe50