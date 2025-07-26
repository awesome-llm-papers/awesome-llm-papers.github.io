---
layout: publication
title: Explaining Black Box Predictions And Unveiling Data Artifacts Through Influence
  Functions
authors: Xiaochuang Han, Byron C. Wallace, Yulia Tsvetkov
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: han2020explaining
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.06676'}]
tags: ["Training Techniques"]
short_authors: Xiaochuang Han, Byron C. Wallace, Yulia Tsvetkov
---
Modern deep learning models for NLP are notoriously opaque. This has
motivated the development of methods for interpreting such models, e.g., via
gradient-based saliency maps or the visualization of attention weights. Such
approaches aim to provide explanations for a particular model prediction by
highlighting important words in the corresponding input text. While this might
be useful for tasks where decisions are explicitly influenced by individual
tokens in the input, we suspect that such highlighting is not suitable for
tasks where model decisions should be driven by more complex reasoning. In this
work, we investigate the use of influence functions for NLP, providing an
alternative approach to interpreting neural text classifiers. Influence
functions explain the decisions of a model by identifying influential training
examples. Despite the promise of this approach, influence functions have not
yet been extensively evaluated in the context of NLP, a gap addressed by this
work. We conduct a comparison between influence functions and common
word-saliency methods on representative tasks. As suspected, we find that
influence functions are particularly useful for natural language inference, a
task in which 'saliency maps' may not have clear interpretation. Furthermore,
we develop a new quantitative measure based on influence functions that can
reveal artifacts in training data.