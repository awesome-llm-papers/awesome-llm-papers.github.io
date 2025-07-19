---
layout: publication
title: 'Beyond Progress Measures: Theoretical Insights Into The Mechanism Of Grokking'
authors: Gu et al.
conference: Social Indicators Research
year: 2025
bibkey: gu2025beyond
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.03162'}]
tags: [RAG, Training Techniques, Tools, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, UAI, Datasets]
---
Grokking, referring to the abrupt improvement in test accuracy after extended
overfitting, offers valuable insights into the mechanisms of model
generalization. Existing researches based on progress measures imply that
grokking relies on understanding the optimization dynamics when the loss
function is dominated solely by the weight decay term. However, we find that
this optimization merely leads to token uniformity, which is not a sufficient
condition for grokking. In this work, we investigate the grokking mechanism
underlying the Transformer in the task of prime number operations. Based on
theoretical analysis and experimental validation, we present the following
insights: (i) The weight decay term encourages uniformity across all tokens in
the embedding space when it is minimized. (ii) The occurrence of grokking is
jointly determined by the uniformity of the embedding space and the
distribution of the training dataset. Building on these insights, we provide a
unified perspective for understanding various previously proposed progress
measures and introduce a novel, concise, and effective progress measure that
could trace the changes in test loss more accurately. Finally, to demonstrate
the versatility of our theoretical framework, we design a dedicated dataset to
validate our theory on ResNet-18, successfully showcasing the occurrence of
grokking. The code is released at https://github.com/Qihuai27/Grokking-Insight.