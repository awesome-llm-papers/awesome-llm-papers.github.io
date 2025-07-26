---
layout: publication
title: 'One Size Does Not Fit All: Generating And Evaluating Variable Number Of Keyphrases'
authors: Xingdi Yuan, Tong Wang, Rui Meng, Khushboo Thaker, Peter Brusilovsky, Daqing
  He, Adam Trischler
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: yuan2018one
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.05241'}]
tags: ["Evaluation"]
short_authors: Yuan et al.
---
Different texts shall by nature correspond to different number of keyphrases.
This desideratum is largely missing from existing neural keyphrase generation
models. In this study, we address this problem from both modeling and
evaluation perspectives.
  We first propose a recurrent generative model that generates multiple
keyphrases as delimiter-separated sequences. Generation diversity is further
enhanced with two novel techniques by manipulating decoder hidden states. In
contrast to previous approaches, our model is capable of generating diverse
keyphrases and controlling number of outputs.
  We further propose two evaluation metrics tailored towards the
variable-number generation. We also introduce a new dataset StackEx that
expands beyond the only existing genre (i.e., academic writing) in keyphrase
generation tasks. With both previous and new evaluation metrics, our model
outperforms strong baselines on all datasets.