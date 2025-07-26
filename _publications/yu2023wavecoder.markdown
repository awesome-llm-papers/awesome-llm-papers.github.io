---
layout: publication
title: 'Wavecoder: Widespread And Versatile Enhanced Instruction Tuning With Refined
  Data Generation'
authors: Zhaojian Yu, Xin Zhang, Ning Shang, Yangyu Huang, Can Xu, Yishujie Zhao,
  Wenxiang Hu, Qiufeng Yin
conference: No Venue
year: 2023
bibkey: yu2023wavecoder
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/658a4687eac1c5dac0efee97'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2312.14187'}]
tags: ["Fine-Tuning", "Has Code", "Llm For Code", "Tools"]
short_authors: Yu et al.
---
Recent work demonstrates that, after being fine-tuned on a high-quality instruction dataset, the resulting model can obtain impressive capabilities to address a wide range of tasks. However, existing methods for instruction data generation often produce duplicate data and are not controllable enough on data quality. In this paper, we extend the generalization of instruction tuning by classifying the instruction data to 4 code-related tasks and propose a LLM-based Generator-Discriminator data process framework to generate diverse, high-quality instruction data from open source code. Hence, we introduce CodeOcean, a dataset comprising 20,000 instruction instances across 4 universal code-related tasks,which is aimed at augmenting the effectiveness of instruction tuning and improving the generalization ability of fine-tuned model. Subsequently, we present WaveCoder, a fine-tuned Code LLM with Widespread And Versatile Enhanced instruction tuning. This model is specifically designed for enhancing instruction tuning of Code Language Models (LLMs). Our experiments demonstrate that Wavecoder models outperform other open-source models in terms of generalization ability across different code-related tasks at the same level of fine-tuning scale. Moreover, Wavecoder exhibits high efficiency in previous code generation tasks. This paper thus offers a significant contribution to the field of instruction data generation and fine-tuning models, providing new insights and tools for enhancing performance in code-related tasks.

https://huggingface.co/discussions/paper/658a4687eac1c5dac0efee97