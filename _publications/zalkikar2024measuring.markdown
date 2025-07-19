---
layout: publication
title: Measuring Social Biases In Masked Language Models By Proxy Of Prediction Quality
authors: Zalkikar Rahul, Chandra Kanchan
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: zalkikar2024measuring
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.13954'}]
tags: [Training Techniques, EMNLP, Masked Language Model, Evaluation, Ethics And Bias,
  Transformer, BERT, Model Architecture, Language Modeling, Datasets]
---
Transformer language models have achieved state-of-the-art performance for a
variety of natural language tasks but have been shown to encode unwanted
biases. We evaluate the social biases encoded by transformers trained with the
masked language modeling objective using proposed proxy functions within an
iterative masking experiment to measure the quality of transformer models'
predictions and assess the preference of MLMs towards disadvantaged and
advantaged groups. We find all models encode concerning social biases. We
compare bias estimations with those produced by other evaluation methods using
benchmark datasets and assess their alignment with human annotated biases. We
extend previous work by evaluating social biases introduced after retraining an
MLM under the masked language modeling objective and find proposed measures
produce more accurate and sensitive estimations of biases introduced by
retraining MLMs based on relative preference for biased sentences between
models, while other methods tend to underestimate biases after retraining on
sentences biased towards disadvantaged groups.