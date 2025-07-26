---
layout: publication
title: 'VLM: Task-agnostic Video-language Model Pre-training For Video Understanding'
authors: Hu Xu, Gargi Ghosh, Po-yao Huang, Prahal Arora, Masoumeh Aminzadeh, Christoph
  Feichtenhofer, Florian Metze, Luke Zettlemoyer
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: xu2021vlm
citations: 69
additional_links: [{name: Code, url: 'https://github.com/pytorch/fairseq/tree/main/examples/MMPT'},
  {name: Paper, url: 'https://arxiv.org/abs/2105.09996'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Xu et al.
---
We present a simplified, task-agnostic multi-modal pre-training approach that
can accept either video or text input, or both for a variety of end tasks.
Existing pre-training are task-specific by adopting either a single cross-modal
encoder that requires both modalities, limiting their use for retrieval-style
end tasks or more complex multitask learning with two unimodal encoders,
limiting early cross-modal fusion. We instead introduce new pretraining masking
schemes that better mix across modalities (e.g. by forcing masks for text to
predict the closest video embeddings) while also maintaining separability (e.g.
unimodal predictions are sometimes required, without using all the input).
Experimental results show strong performance across a wider range of tasks than
any previous methods, often outperforming task-specific pre-training. Code is
made available at https://github.com/pytorch/fairseq/tree/main/examples/MMPT.