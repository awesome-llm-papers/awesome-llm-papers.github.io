---
layout: publication
title: Attention-guided Answer Distillation For Machine Reading Comprehension
authors: Hu et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: hu2018attention
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.07644'}]
tags: [RAG, EMNLP, Attention Mechanism, Training Techniques, Distillation, Evaluation,
  Model Architecture, Efficiency And Optimization, Security, Datasets]
---
Despite that current reading comprehension systems have achieved significant
advancements, their promising performances are often obtained at the cost of
making an ensemble of numerous models. Besides, existing approaches are also
vulnerable to adversarial attacks. This paper tackles these problems by
leveraging knowledge distillation, which aims to transfer knowledge from an
ensemble model to a single model. We first demonstrate that vanilla knowledge
distillation applied to answer span prediction is effective for reading
comprehension systems. We then propose two novel approaches that not only
penalize the prediction on confusing answers but also guide the training with
alignment information distilled from the ensemble. Experiments show that our
best student model has only a slight drop of 0.4% F1 on the SQuAD test set
compared to the ensemble teacher, while running 12x faster during inference. It
even outperforms the teacher on adversarial SQuAD datasets and NarrativeQA
benchmark.