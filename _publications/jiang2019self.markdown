---
layout: publication
title: Self-assembling Modular Networks For Interpretable Multi-hop Reasoning
authors: Yichen Jiang, Mohit Bansal
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: jiang2019self
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.05803'}]
tags: ["EMNLP", "Memory & Context"]
short_authors: Yichen Jiang, Mohit Bansal
---
Multi-hop QA requires a model to connect multiple pieces of evidence
scattered in a long context to answer the question. The recently proposed
HotpotQA (Yang et al., 2018) dataset is comprised of questions embodying four
different multi-hop reasoning paradigms (two bridge entity setups, checking
multiple properties, and comparing two entities), making it challenging for a
single neural network to handle all four. In this work, we present an
interpretable, controller-based Self-Assembling Neural Modular Network (Hu et
al., 2017, 2018) for multi-hop reasoning, where we design four novel modules
(Find, Relocate, Compare, NoOp) to perform unique types of language reasoning.
Based on a question, our layout controller RNN dynamically infers a series of
reasoning modules to construct the entire network. Empirically, we show that
our dynamic, multi-hop modular network achieves significant improvements over
the static, single-hop baseline (on both regular and adversarial evaluation).
We further demonstrate the interpretability of our model via three analyses.
First, the controller can softly decompose the multi-hop question into multiple
single-hop sub-questions to promote compositional reasoning behavior of the
main network. Second, the controller can predict layouts that conform to the
layouts designed by human experts. Finally, the intermediate module can infer
the entity that connects two distantly-located supporting facts by addressing
the sub-question from the controller.