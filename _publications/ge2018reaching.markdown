---
layout: publication
title: 'Reaching Human-level Performance In Automatic Grammatical Error Correction:
  An Empirical Study'
authors: Tao Ge, Furu Wei, Ming Zhou
conference: Arxiv
year: 2018
bibkey: ge2018reaching
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.01270'}]
tags: ["Datasets", "Evaluation", "Tools", "Training Techniques"]
short_authors: Tao Ge, Furu Wei, Ming Zhou
---
Neural sequence-to-sequence (seq2seq) approaches have proven to be successful
in grammatical error correction (GEC). Based on the seq2seq framework, we
propose a novel fluency boost learning and inference mechanism. Fluency
boosting learning generates diverse error-corrected sentence pairs during
training, enabling the error correction model to learn how to improve a
sentence's fluency from more instances, while fluency boosting inference allows
the model to correct a sentence incrementally with multiple inference steps.
Combining fluency boost learning and inference with convolutional seq2seq
models, our approach achieves the state-of-the-art performance: 75.72 (F_\{0.5\})
on CoNLL-2014 10 annotation dataset and 62.42 (GLEU) on JFLEG test set
respectively, becoming the first GEC system that reaches human-level
performance (72.58 for CoNLL and 62.37 for JFLEG) on both of the benchmarks.