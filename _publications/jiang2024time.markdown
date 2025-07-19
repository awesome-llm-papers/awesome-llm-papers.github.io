---
layout: publication
title: 'Time Matters: Enhancing Pre-trained News Recommendation Models With Robust
  User Dwell Time Injection'
authors: Jiang Hao, Li Chuanzhen, An Mingxiao
conference: Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: jiang2024time
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.12486'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Reinforcement Learning,
  SIGIR, Security, Datasets]
---
Large Language Models (LLMs) have revolutionized text comprehension, leading
to State-of-the-Art (SOTA) news recommendation models that utilize LLMs for
in-depth news understanding. Despite this, accurately modeling user preferences
remains challenging due to the inherent uncertainty of click behaviors.
Techniques like multi-head attention in Transformers seek to alleviate this by
capturing interactions among clicks, yet they fall short in integrating
explicit feedback signals. User Dwell Time emerges as a powerful indicator,
offering the potential to enhance the weak signals emanating from clicks.
Nonetheless, its real-world applicability is questionable, especially when
dwell time data collection is subject to delays. To bridge this gap, this paper
proposes two novel and robust dwell time injection strategies, namely Dwell
time Weight (DweW) and Dwell time Aware (DweA). Dwe\} concentrates on refining
Effective User Clicks through detailed analysis of dwell time, integrating with
initial behavioral inputs to construct a more robust user preference. DweA
empowers the model with awareness of dwell time information, thereby
facilitating autonomous adjustment of attention values in user modeling. This
enhancement sharpens the model's ability to accurately identify user
preferences. In our experiment using the real-world news dataset from MSN
website, we validated that our two strategies significantly improve
recommendation performance, favoring high-quality news. Crucially, our
approaches exhibit robustness to user dwell time information, maintaining their
ability to recommend high-quality content even in extreme cases where dwell
time data is entirely missing.