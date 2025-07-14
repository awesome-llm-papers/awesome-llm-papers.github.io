---
layout: publication
title: Exploring The Limits Of Transfer Learning With A Unified Text-to-text Transformer
authors: Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael
  Matena, Yanqi Zhou, Wei Li, Peter J. Liu
conference: Arxiv
year: 2019
bibkey: colin2019exploring
citations: 8131
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/1910.10683v4'}]
tags: [Model Architecture, Evaluation, Fine Tuning, Transformer, Datasets, Tools,
  Training Techniques]
---
Transfer learning, where a model is first pre-trained on a data-rich task
before being fine-tuned on a downstream task, has emerged as a powerful
technique in natural language processing (NLP). The effectiveness of transfer
learning has given rise to a diversity of approaches, methodology, and
practice. In this paper, we explore the landscape of transfer learning
techniques for NLP by introducing a unified framework that converts all
text-based language problems into a text-to-text format. Our systematic study
compares pre-training objectives, architectures, unlabeled data sets, transfer
approaches, and other factors on dozens of language understanding tasks. By
combining the insights from our exploration with scale and our new ``Colossal
Clean Crawled Corpus'', we achieve state-of-the-art results on many benchmarks
covering summarization, question answering, text classification, and more. To
facilitate future work on transfer learning for NLP, we release our data set,
pre-trained models, and code.