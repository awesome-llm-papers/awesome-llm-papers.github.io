---
layout: publication
title: 'Evaluating Explanations: How Much Do Explanations From The Teacher Aid Students?'
authors: Pruthi et al.
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: pruthi2020evaluating
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.00893'}]
tags: [Model Architecture, Tools, Interpretability And Explainability, Training Techniques,
  Evaluation, TACL, ACL]
---
While many methods purport to explain predictions by highlighting salient
features, what aims these explanations serve and how they ought to be evaluated
often go unstated. In this work, we introduce a framework to quantify the value
of explanations via the accuracy gains that they confer on a student model
trained to simulate a teacher model. Crucially, the explanations are available
to the student during training, but are not available at test time. Compared to
prior proposals, our approach is less easily gamed, enabling principled,
automatic, model-agnostic evaluation of attributions. Using our framework, we
compare numerous attribution methods for text classification and question
answering, and observe quantitative differences that are consistent (to a
moderate to high degree) across different student model architectures and
learning strategies.