---
layout: publication
title: Augmented Natural Language For Generative Sequence Labeling
authors: Athiwaratkun et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: athiwaratkun2020augmented
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.13272'}]
tags: [EMNLP, Tools, Evaluation, BERT, Model Architecture, Few Shot, NEURIPS, Datasets]
---
We propose a generative framework for joint sequence labeling and
sentence-level classification. Our model performs multiple sequence labeling
tasks at once using a single, shared natural language output space. Unlike
prior discriminative methods, our model naturally incorporates label semantics
and shares knowledge across tasks. Our framework is general purpose, performing
well on few-shot, low-resource, and high-resource tasks. We demonstrate these
advantages on popular named entity recognition, slot labeling, and intent
classification benchmarks. We set a new state-of-the-art for few-shot slot
labeling, improving substantially upon the previous 5-shot (\\(75.0% \rightarrow
90.9%\\)) and 1-shot (\\(70.4% \rightarrow 81.0%\\)) state-of-the-art results.
Furthermore, our model generates large improvements (\\(46.27% \rightarrow
63.83%\\)) in low-resource slot labeling over a BERT baseline by incorporating
label semantics. We also maintain competitive results on high-resource tasks,
performing within two points of the state-of-the-art on all tasks and setting a
new state-of-the-art on the SNIPS dataset.