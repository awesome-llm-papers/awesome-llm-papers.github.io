---
layout: publication
title: Guiding Attention In Sequence-to-sequence Models For Dialogue Act Prediction
authors: Colombo et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: colombo2020guiding
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.08801'}]
tags: [RAG, Training Techniques, Attention Mechanism, Agentic, Model Architecture,
  AAAI]
---
The task of predicting dialog acts (DA) based on conversational dialog is a
key component in the development of conversational agents. Accurately
predicting DAs requires a precise modeling of both the conversation and the
global tag dependencies. We leverage seq2seq approaches widely adopted in
Neural Machine Translation (NMT) to improve the modelling of tag sequentiality.
Seq2seq models are known to learn complex global dependencies while currently
proposed approaches using linear conditional random fields (CRF) only model
local tag dependencies. In this work, we introduce a seq2seq model tailored for
DA classification using: a hierarchical encoder, a novel guided attention
mechanism and beam search applied to both training and inference. Compared to
the state of the art our model does not require handcrafted features and is
trained end-to-end. Furthermore, the proposed approach achieves an unmatched
accuracy score of 85% on SwDA, and state-of-the-art accuracy score of 91.6% on
MRDA.