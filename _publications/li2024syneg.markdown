---
layout: publication
title: 'Syneg: Llm-driven Synthetic Hard-negatives For Dense Retrieval'
authors: Li et al.
conference: Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: li2024syneg
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.17250'}]
tags: [Training Techniques, Prompting, Tools, Evaluation, SIGIR, Datasets]
---
The performance of Dense retrieval (DR) is significantly influenced by the
quality of negative sampling. Traditional DR methods primarily depend on naive
negative sampling techniques or on mining hard negatives through external
retriever and meticulously crafted strategies. However, naive negative sampling
often fails to adequately capture the accurate boundaries between positive and
negative samples, whereas existing hard negative sampling methods are prone to
false negatives, resulting in performance degradation and training instability.
Recent advancements in large language models (LLMs) offer an innovative
solution to these challenges by generating contextually rich and diverse
negative samples. In this work, we present a framework that harnesses LLMs to
synthesize high-quality hard negative samples. We first devise a
\textit\{multi-attribute self-reflection prompting strategy\} to direct LLMs in
hard negative sample generation. Then, we implement a \textit\{hybrid sampling
strategy\} that integrates these synthetic negatives with traditionally
retrieved negatives, thereby stabilizing the training process and improving
retrieval performance. Extensive experiments on five benchmark datasets
demonstrate the efficacy of our approach, and code is also publicly available.