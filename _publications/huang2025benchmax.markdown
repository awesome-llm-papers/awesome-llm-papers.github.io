---
layout: publication
title: 'Benchmax: A Comprehensive Multilingual Evaluation Suite For Large Language
  Models'
authors: Xu Huang, Wenhao Zhu, Hanxu Hu, Conghui He, Lei Li, Shujian Huang, Fei Yuan
conference: No Venue
year: 2025
bibkey: huang2025benchmax
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ac4e056b8c86e0cc798952'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.07346'}]
tags: ["Evaluation", "Tools"]
short_authors: Huang et al.
---
Previous multilingual benchmarks focus primarily on simple understanding tasks, but for large language models(LLMs), we emphasize proficiency in instruction following, reasoning, long context understanding, code generation, and so on. However, measuring these advanced capabilities across languages is underexplored. To address the disparity, we introduce BenchMAX, a multi-way multilingual evaluation benchmark that allows for fair comparisons of these important abilities across languages. To maintain high quality, three distinct native-speaking annotators independently annotate each sample within all tasks after the data was machine-translated from English into 16 other languages. Additionally, we present a novel translation challenge stemming from dataset construction. Extensive experiments on BenchMAX reveal varying effectiveness of core capabilities across languages, highlighting performance gaps that cannot be bridged by simply scaling up model size. BenchMAX serves as a comprehensive multilingual evaluation platform, providing a promising test bed to promote the development of multilingual language models. The dataset and code are publicly accessible.

https://huggingface.co/discussions/paper/67ac4e056b8c86e0cc798952