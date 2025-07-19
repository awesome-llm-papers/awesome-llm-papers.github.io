---
layout: publication
title: 'Knowing Where To Focus: Attention-guided Alignment For Text-based Person Search'
authors: Tan et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: tan2024knowing
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.15106'}]
tags: [Training Techniques, Attention Mechanism, Masked Language Model, Tools, Evaluation,
  BERT, Model Architecture, Language Modeling, Multimodal Models, AAAI, Datasets]
---
In the realm of Text-Based Person Search (TBPS), mainstream methods aim to
explore more efficient interaction frameworks between text descriptions and
visual data. However, recent approaches encounter two principal challenges.
Firstly, the widely used random-based Masked Language Modeling (MLM) considers
all the words in the text equally during training. However, massive
semantically vacuous words ('with', 'the', etc.) be masked fail to contribute
efficient interaction in the cross-modal MLM and hampers the representation
alignment. Secondly, manual descriptions in TBPS datasets are tedious and
inevitably contain several inaccuracies. To address these issues, we introduce
an Attention-Guided Alignment (AGA) framework featuring two innovative
components: Attention-Guided Mask (AGM) Modeling and Text Enrichment Module
(TEM). AGM dynamically masks semantically meaningful words by aggregating the
attention weight derived from the text encoding process, thereby cross-modal
MLM can capture information related to the masked word from text context and
images and align their representations. Meanwhile, TEM alleviates low-quality
representations caused by repetitive and erroneous text descriptions by
replacing those semantically meaningful words with MLM's prediction. It not
only enriches text descriptions but also prevents overfitting. Extensive
experiments across three challenging benchmarks demonstrate the effectiveness
of our AGA, achieving new state-of-the-art results with Rank-1 accuracy
reaching 78.36%, 67.31%, and 67.4% on CUHK-PEDES, ICFG-PEDES, and RSTPReid,
respectively.