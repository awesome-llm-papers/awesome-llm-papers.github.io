---
layout: publication
title: 'GRADE: Automatic Graph-enhanced Coherence Metric For Evaluating Open-domain
  Dialogue Systems'
authors: Huang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: huang2020grade
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.03994'}]
tags: [EMNLP, Attention Mechanism, Tools, Evaluation, Model Architecture, Reinforcement
    Learning, Datasets]
---
Automatically evaluating dialogue coherence is a challenging but high-demand
ability for developing high-quality open-domain dialogue systems. However,
current evaluation metrics consider only surface features or utterance-level
semantics, without explicitly considering the fine-grained topic transition
dynamics of dialogue flows. Here, we first consider that the graph structure
constituted with topics in a dialogue can accurately depict the underlying
communication logic, which is a more natural way to produce persuasive metrics.
Capitalized on the topic-level dialogue graph, we propose a new evaluation
metric GRADE, which stands for Graph-enhanced Representations for Automatic
Dialogue Evaluation. Specifically, GRADE incorporates both coarse-grained
utterance-level contextualized representations and fine-grained topic-level
graph representations to evaluate dialogue coherence. The graph representations
are obtained by reasoning over topic-level dialogue graphs enhanced with the
evidence from a commonsense graph, including k-hop neighboring representations
and hop-attention weights. Experimental results show that our GRADE
significantly outperforms other state-of-the-art metrics on measuring diverse
dialogue models in terms of the Pearson and Spearman correlations with human
judgements. Besides, we release a new large-scale human evaluation benchmark to
facilitate future research on automatic metrics.