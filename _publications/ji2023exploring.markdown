---
layout: publication
title: 'Exploring The Impact Of Instruction Data Scaling On Large Language Models:
  An Empirical Study On Real-world Use Cases'
authors: Yunjie Ji et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: ji2023exploring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14742'}]
tags: [Training Techniques, GPT, Fine-Tuning, Reinforcement Learning, Applications,
  Model Architecture]
---
The success of ChatGPT has recently attracted numerous efforts to replicate
it, with instruction-tuning strategies being a key factor in achieving
remarkable results. Instruction-tuning not only significantly enhances the
model's performance and generalization but also makes the model's generated
results more consistent with human speech patterns. However current research
rarely studies the impact of different amounts of instruction data on model
performance, especially in the real-world use cases. In this paper we explore
the performance of large language models based on instruction tuning across
different scales of instruction data. An evaluation dataset consisting of 12
major online use cases is constructed in the experiment. With Bloomz-7B1-mt as
the base model, the results show that 1) merely increasing the amount of
instruction data leads to continuous improvement in tasks such as open-ended
generation, 2) in tasks such as math and code, the model performance curve
remains quite flat while increasing data size. We further analyze the possible
causes of these phenomena and propose potential future research directions such
as effectively selecting high-quality training data, scaling base models and
training methods specialized for hard tasks. We will release our training and
evaluation datasets, as well as model checkpoints.