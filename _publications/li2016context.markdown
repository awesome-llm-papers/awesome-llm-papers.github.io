---
layout: publication
title: A Context-aware Attention Network For Interactive Question Answering
authors: Li et al.
conference: Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge
  Discovery and Data Mining
year: 2016
bibkey: li2016context
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.07411'}]
tags: [Attention Mechanism, Tools, Transformer, Model Architecture, Datasets, KDD]
---
Neural network based sequence-to-sequence models in an encoder-decoder
framework have been successfully applied to solve Question Answering (QA)
problems, predicting answers from statements and questions. However, almost all
previous models have failed to consider detailed context information and
unknown states under which systems do not have enough information to answer
given questions. These scenarios with incomplete or ambiguous information are
very common in the setting of Interactive Question Answering (IQA). To address
this challenge, we develop a novel model, employing context-dependent
word-level attention for more accurate statement representations and
question-guided sentence-level attention for better context modeling. We also
generate unique IQA datasets to test our model, which will be made publicly
available. Employing these attention mechanisms, our model accurately
understands when it can output an answer or when it requires generating a
supplementary question for additional input depending on different contexts.
When available, user's feedback is encoded and directly applied to update
sentence-level attention to infer an answer. Extensive experiments on QA and
IQA datasets quantitatively demonstrate the effectiveness of our model with
significant improvement over state-of-the-art conventional QA models.