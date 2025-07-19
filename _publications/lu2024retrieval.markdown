---
layout: publication
title: Retrieval Augmented Cross-modal Tag Recommendation In Software Q&A Sites
authors: Lu et al.
conference: 2013 10th Working Conference on Mining Software Repositories (MSR)
year: 2024
bibkey: lu2024retrieval
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.03635'}]
tags: [RAG, Attention Mechanism, Model Architecture, Reinforcement Learning, Multimodal
    Models, Datasets, Merging]
---
Posts in software Q\&A sites often consist of three main parts: title,
description and code, which are interconnected and jointly describe the
question. Existing tag recommendation methods often treat different modalities
as a whole or inadequately consider the interaction between different
modalities. Additionally, they focus on extracting information directly from
the post itself, neglecting the information from external knowledge sources.
Therefore, we propose a Retrieval Augmented Cross-Modal (RACM) Tag
Recommendation Model in Software Q\&A Sites. Specifically, we first use the
input post as a query and enhance the representation of different modalities by
retrieving information from external knowledge sources. For the
retrieval-augmented representations, we employ a cross-modal context-aware
attention to leverage the main modality description for targeted feature
extraction across the submodalities title and code. In the fusion process, a
gate mechanism is employed to achieve fine-grained feature selection,
controlling the amount of information extracted from the submodalities.
Finally, the fused information is used for tag recommendation. Experimental
results on three real-world datasets demonstrate that our model outperforms the
state-of-the-art counterparts.