---
layout: publication
title: GPT-4 Technical Report
authors: Openai et al.
conference: Arxiv
year: 2023
citations: 1402
bibkey: openai2023gpt
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2303.08774v6'}]
tags: [Model Architecture, GPT, Transformer, Reinforcement Learning, Multimodal Models,
  Efficiency and Optimization, Training Techniques, Evaluation]
---
We report the development of GPT-4, a large-scale, multimodal model which can
accept image and text inputs and produce text outputs. While less capable than
humans in many real-world scenarios, GPT-4 exhibits human-level performance on
various professional and academic benchmarks, including passing a simulated bar
exam with a score around the top 10% of test takers. GPT-4 is a
Transformer-based model pre-trained to predict the next token in a document.
The post-training alignment process results in improved performance on measures
of factuality and adherence to desired behavior. A core component of this
project was developing infrastructure and optimization methods that behave
predictably across a wide range of scales. This allowed us to accurately
predict some aspects of GPT-4's performance based on models trained with no
more than 1/1,000th the compute of GPT-4.