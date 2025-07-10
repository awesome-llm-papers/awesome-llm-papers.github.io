---
layout: publication
title: Contrastive Learning With Bidirectional Transformers For Sequential Recommendation
authors: Hanwen Du et al.
conference: 'CIKM ''22: The 31st ACM International Conference on Information and Knowledge
  Management'
year: 2022
citations: 39
bibkey: du2022contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.03895'}]
tags: [Model Architecture, Transformer, Tools, BERT, Evaluation]
---
Contrastive learning with Transformer-based sequence encoder has gained
predominance for sequential recommendation. It maximizes the agreements between
paired sequence augmentations that share similar semantics. However, existing
contrastive learning approaches in sequential recommendation mainly center upon
left-to-right unidirectional Transformers as base encoders, which are
suboptimal for sequential recommendation because user behaviors may not be a
rigid left-to-right sequence. To tackle that, we propose a novel framework
named \textbf\{C\}ontrastive learning with \textbf\{Bi\}directional
\textbf\{T\}ransformers for sequential recommendation (\textbf\{CBiT\}).
Specifically, we first apply the slide window technique for long user sequences
in bidirectional Transformers, which allows for a more fine-grained division of
user sequences. Then we combine the cloze task mask and the dropout mask to
generate high-quality positive samples and perform multi-pair contrastive
learning, which demonstrates better performance and adaptability compared with
the normal one-pair contrastive learning. Moreover, we introduce a novel
dynamic loss reweighting strategy to balance between the cloze task loss and
the contrastive loss. Experiment results on three public benchmark datasets
show that our model outperforms state-of-the-art models for sequential
recommendation.