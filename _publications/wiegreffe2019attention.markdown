---
layout: publication
title: Attention Is Not Not Explanation
authors: Sarah Wiegreffe, Yuval Pinter
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: wiegreffe2019attention
citations: 753
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.04626'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Sarah Wiegreffe, Yuval Pinter
---
Attention mechanisms play a central role in NLP systems, especially within
recurrent neural network (RNN) models. Recently, there has been increasing
interest in whether or not the intermediate representations offered by these
modules may be used to explain the reasoning for a model's prediction, and
consequently reach insights regarding the model's decision-making process. A
recent paper claims that `Attention is not Explanation' (Jain and Wallace,
2019). We challenge many of the assumptions underlying this work, arguing that
such a claim depends on one's definition of explanation, and that testing it
needs to take into account all elements of the model, using a rigorous
experimental design. We propose four alternative tests to determine
when/whether attention can be used as explanation: a simple uniform-weights
baseline; a variance calibration based on multiple random seed runs; a
diagnostic framework using frozen weights from pretrained models; and an
end-to-end adversarial attention training protocol. Each allows for meaningful
interpretation of attention mechanisms in RNN models. We show that even when
reliable adversarial distributions can be found, they don't perform well on the
simple diagnostic, indicating that prior work does not disprove the usefulness
of attention mechanisms for explainability.