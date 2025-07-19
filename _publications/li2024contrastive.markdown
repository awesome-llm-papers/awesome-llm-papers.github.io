---
layout: publication
title: Contrastive Pre-training For Deep Session Data Understanding
authors: Li et al.
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: li2024contrastive
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.02825'}]
tags: [RAG, Training Techniques, EMNLP, Security]
---
Session data has been widely used for understanding user's behavior in
e-commerce. Researchers are trying to leverage session data for different
tasks, such as purchase intention prediction, remaining length prediction,
recommendation, etc., as it provides context clues about the user's dynamic
interests. However, online shopping session data is semi-structured and complex
in nature, which contains both unstructured textual data about the products,
search queries, and structured user action sequences. Most existing works focus
on leveraging the coarse-grained item sequences for specific tasks, while
largely ignore the fine-grained information from text and user action details.
In this work, we delve into deep session data understanding via scrutinizing
the various clues inside the rich information in user sessions. Specifically,
we propose to pre-train a general-purpose User Behavior Model (UBM) over
large-scale session data with rich details, such as product title, attributes
and various kinds of user actions. A two-stage pre-training scheme is
introduced to encourage the model to self-learn from various augmentations with
contrastive learning objectives, which spans different granularity levels of
session data. Then the well-trained session understanding model can be easily
fine-tuned for various downstream tasks. Extensive experiments show that UBM
better captures the complex intra-item semantic relations, inter-item
connections and inter-interaction dependencies, leading to large performance
gains as compared to the baselines on several downstream tasks. And it also
demonstrates strong robustness when data is sparse.