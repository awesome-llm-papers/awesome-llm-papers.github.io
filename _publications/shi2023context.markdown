---
layout: publication
title: 'In-context Pretraining: Language Modeling Beyond Document Boundaries'
authors: Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Victoria
  Lin, Noah A. Smith, Luke Zettlemoyer, Scott Yih, Mike Lewis
conference: No Venue
year: 2023
bibkey: shi2023context
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2310.10638'}]
tags: ["In Context Learning"]
short_authors: Shi et al.
---
Large language models (LMs) are currently trained to predict tokens given document prefixes, enabling them to directly perform long-form generation and prompting-style tasks which can be reduced to document completion. Existing pretraining pipelines train LMs by concatenating random sets of short documents to create input contexts but the prior documents provide no signal for predicting the next document. We instead present In-Context Pretraining, a new approach where language models are pretrained on a sequence of related documents, thereby explicitly encouraging them to read and reason across document boundaries. We can do In-Context Pretraining by simply changing the document ordering so that each context contains related documents, and directly applying existing pretraining pipelines. However, this document sorting problem is challenging. There are billions of documents and we would like the sort to maximize contextual similarity for every document without repeating any data. To do this, we introduce approximate algorithms for finding related documents with efficient nearest neighbor search and constructing coherent input contexts with a graph traversal algorithm. Our experiments show In-Context Pretraining offers a simple and scalable approach to significantly enhance LMs'performance: we see notable improvements in tasks that require more complex contextual reasoning, including in-context learning (+8%), reading comprehension (+15%), faithfulness to previous contexts (+16%), long-context reasoning (+5%), and retrieval augmentation (+9%).

https://huggingface.co/discussions/paper/652e0ccfb86e108d0ff3c2c4