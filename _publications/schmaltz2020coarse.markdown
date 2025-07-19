---
layout: publication
title: Coarse-to-fine Memory Matching For Joint Retrieval And Classification
authors: Schmaltz Allen, Beam Andrew
conference: IEEE Transactions on Systems, Man, and Cybernetics
year: 2020
bibkey: schmaltz2020coarse
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.02287'}]
tags: [Model Architecture, Training Techniques, BERT, Evaluation, RAG, Ethics and
    Bias, Datasets]
---
We present a novel end-to-end language model for joint retrieval and
classification, unifying the strengths of bi- and cross- encoders into a single
language model via a coarse-to-fine memory matching search procedure for
learning and inference. Evaluated on the standard blind test set of the FEVER
fact verification dataset, classification accuracy is significantly higher than
approaches that only rely on the language model parameters as a knowledge base,
and approaches some recent multi-model pipeline systems, using only a single
BERT base model augmented with memory layers. We further demonstrate how
coupled retrieval and classification can be leveraged to identify low
confidence instances, and we extend exemplar auditing to this setting for
analyzing and constraining the model. As a result, our approach yields a means
of updating language model behavior through two distinct mechanisms: The
retrieved information can be updated explicitly, and the model behavior can be
modified via the exemplar database.