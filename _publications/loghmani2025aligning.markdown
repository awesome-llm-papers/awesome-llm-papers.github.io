---
layout: publication
title: 'Aligning Language Models With Observational Data: Opportunities And Risks
  From A Causal Perspective'
authors: Loghmani Erfan
conference: Community Dentistry and Oral Epidemiology
year: 2025
bibkey: loghmani2025aligning
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00152'}]
tags: [Training Techniques, Evaluation, Reinforcement Learning, Fine Tuning, Datasets]
---
Large language models are being widely used across industries to generate content that contributes directly to key performance metrics, such as conversion rates. Pretrained models, however, often fall short when it comes to aligning with human preferences or optimizing for business objectives. As a result, fine-tuning with good-quality labeled data is essential to guide models to generate content that achieves better results. Controlled experiments, like A/B tests, can provide such data, but they are often expensive and come with significant engineering and logistical challenges. Meanwhile, companies have access to a vast amount of historical (observational) data that remains underutilized. In this work, we study the challenges and opportunities of fine-tuning LLMs using observational data. We show that while observational outcomes can provide valuable supervision, directly fine-tuning models on such data can lead them to learn spurious correlations. We present empirical evidence of this issue using various real-world datasets and propose DeconfoundLM, a method that explicitly removes the effect of known confounders from reward signals. Using simulation experiments, we demonstrate that DeconfoundLM improves the recovery of causal relationships and mitigates failure modes found in fine-tuning methods that ignore or naively incorporate confounding variables. Our findings highlight that while observational data presents risks, with the right causal corrections, it can be a powerful source of signal for LLM alignment. Please refer to the project page for code and related resources.