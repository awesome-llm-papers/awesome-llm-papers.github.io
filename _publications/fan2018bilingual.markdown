---
layout: publication
title: '"bilingual Expert" Can Find Translation Errors'
authors: Fan et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: fan2018bilingual
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.09433'}]
tags: [Tools, Evaluation, BERT, Transformer, Model Architecture, AAAI, Datasets]
---
Recent advances in statistical machine translation via the adoption of neural
sequence-to-sequence models empower the end-to-end system to achieve
state-of-the-art in many WMT benchmarks. The performance of such machine
translation (MT) system is usually evaluated by automatic metric BLEU when the
golden references are provided for validation. However, for model inference or
production deployment, the golden references are prohibitively available or
require expensive human annotation with bilingual expertise. In order to
address the issue of quality evaluation (QE) without reference, we propose a
general framework for automatic evaluation of translation output for most WMT
quality evaluation tasks. We first build a conditional target language model
with a novel bidirectional transformer, named neural bilingual expert model,
which is pre-trained on large parallel corpora for feature extraction. For QE
inference, the bilingual expert model can simultaneously produce the joint
latent representation between the source and the translation, and real-valued
measurements of possible erroneous tokens based on the prior knowledge learned
from parallel data. Subsequently, the features will further be fed into a
simple Bi-LSTM predictive model for quality evaluation. The experimental
results show that our approach achieves the state-of-the-art performance in the
quality estimation track of WMT 2017/2018.