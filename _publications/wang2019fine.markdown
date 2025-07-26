---
layout: publication
title: Fine-tune Bert For Docred With Two-step Process
authors: Hong Wang, Christfried Focke, Rob Sylvester, Nilesh Mishra, William Wang
conference: Arxiv
year: 2019
bibkey: wang2019fine
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.11898'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Wang et al.
---
Modelling relations between multiple entities has attracted increasing
attention recently, and a new dataset called DocRED has been collected in order
to accelerate the research on the document-level relation extraction. Current
baselines for this task uses BiLSTM to encode the whole document and are
trained from scratch. We argue that such simple baselines are not strong enough
to model to complex interaction between entities. In this paper, we further
apply a pre-trained language model (BERT) to provide a stronger baseline for
this task. We also find that solving this task in phases can further improve
the performance. The first step is to predict whether or not two entities have
a relation, the second step is to predict the specific relation.