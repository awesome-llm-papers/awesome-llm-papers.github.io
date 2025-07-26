---
layout: publication
title: 'Sentence Encoders On Stilts: Supplementary Training On Intermediate Labeled-data
  Tasks'
authors: "Jason Phang, Thibault F\xE9vry, Samuel R. Bowman"
conference: Arxiv
year: 2018
bibkey: phang2018sentence
citations: 291
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.01088'}]
tags: ["Training Techniques"]
short_authors: "Jason Phang, Thibault F\xE9vry, Samuel R. Bowman"
---
Pretraining sentence encoders with language modeling and related unsupervised
tasks has recently been shown to be very effective for language understanding
tasks. By supplementing language model-style pretraining with further training
on data-rich supervised tasks, such as natural language inference, we obtain
additional performance improvements on the GLUE benchmark. Applying
supplementary training on BERT (Devlin et al., 2018), we attain a GLUE score of
81.8---the state of the art (as of 02/24/2019) and a 1.4 point improvement over
BERT. We also observe reduced variance across random restarts in this setting.
Our approach yields similar improvements when applied to ELMo (Peters et al.,
2018a) and Radford et al. (2018)'s model. In addition, the benefits of
supplementary training are particularly pronounced in data-constrained regimes,
as we show in experiments with artificially limited training data.