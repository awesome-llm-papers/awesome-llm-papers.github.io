---
layout: publication
title: 'Easy Dataset: A Unified And Extensible Framework For Synthesizing LLM Fine-tuning
  Data From Unstructured Documents'
authors: Ziyang Miao, Qiyu Sun, Jingyuan Wang, Yuchen Gong, Yaowei Zheng, Shiqi Li,
  Richong Zhang
conference: No Venue
year: 2025
bibkey: miao2025easy
additional_links: [{name: Code, url: 'https://github.com/ConardLi/easy-dataset'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/686cd234cc230c60b4100af3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.04009'}]
tags: ["Datasets", "Fine-Tuning", "Has Code", "Tools"]
short_authors: Miao et al.
---
Large language models (LLMs) have shown impressive performance on general-purpose tasks, yet adapting them to specific domains remains challenging due to the scarcity of high-quality domain data. Existing data synthesis tools often struggle to extract reliable fine-tuning data from heterogeneous documents effectively. To address this limitation, we propose Easy Dataset, a unified framework for synthesizing fine-tuning data from unstructured documents via an intuitive graphical user interface (GUI). Specifically, Easy Dataset allows users to easily configure text extraction models and chunking strategies to transform raw documents into coherent text chunks. It then leverages a persona-driven prompting approach to generate diverse question-answer pairs using public-available LLMs. Throughout the pipeline, a human-in-the-loop visual interface facilitates the review and refinement of intermediate outputs to ensure data quality. Experiments on a financial question-answering task show that fine-tuning LLMs on the synthesized dataset significantly improves domain-specific performance while preserving general knowledge. The source code and installable package are available at https://github.com/ConardLi/easy-dataset and have garnered over 9,000 GitHub stars.

https://huggingface.co/discussions/paper/686cd234cc230c60b4100af3