---
layout: publication
title: 'Phi-3 Technical Report: A Highly Capable Language Model Locally On Your Phone'
authors: Abdin et al.
conference: Arxiv
year: 2024
bibkey: abdin2024phi
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.14219'}]
tags: [Datasets, Training Techniques, GPT, Prompting, Evaluation, Model Architecture,
  Security, Multimodal Models, Responsible AI]
---
We introduce phi-3-mini, a 3.8 billion parameter language model trained on
3.3 trillion tokens, whose overall performance, as measured by both academic
benchmarks and internal testing, rivals that of models such as Mixtral 8x7B and
GPT-3.5 (e.g., phi-3-mini achieves 69% on MMLU and 8.38 on MT-bench), despite
being small enough to be deployed on a phone. Our training dataset is a
scaled-up version of the one used for phi-2, composed of heavily filtered
publicly available web data and synthetic data. The model is also further
aligned for robustness, safety, and chat format. We also provide
parameter-scaling results with a 7B, 14B models trained for 4.8T tokens, called
phi-3-small, phi-3-medium, both significantly more capable than phi-3-mini
(e.g., respectively 75%, 78% on MMLU, and 8.7, 8.9 on MT-bench). To enhance
multilingual, multimodal, and long-context capabilities, we introduce three
models in the phi-3.5 series: phi-3.5-mini, phi-3.5-MoE, and phi-3.5-Vision.
The phi-3.5-MoE, a 16 x 3.8B MoE model with 6.6 billion active parameters,
achieves superior performance in language reasoning, math, and code tasks
compared to other open-source models of similar scale, such as Llama 3.1 and
the Mixtral series, and on par with Gemini-1.5-Flash and GPT-4o-mini.
Meanwhile, phi-3.5-Vision, a 4.2 billion parameter model derived from
phi-3.5-mini, excels in reasoning tasks and is adept at handling both
single-image and text prompts, as well as multi-image and text prompts.