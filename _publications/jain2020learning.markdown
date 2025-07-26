---
layout: publication
title: Learning To Faithfully Rationalize By Construction
authors: Sarthak Jain, Sarah Wiegreffe, Yuval Pinter, Byron C. Wallace
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: jain2020learning
citations: 145
additional_links: [{name: Code, url: 'https://github.com/successar/FRESH'}, {name: Paper,
    url: 'https://arxiv.org/abs/2005.00115'}]
tags: ["Ethics & Fairness", "Has Code", "Tools", "Training Techniques"]
short_authors: Jain et al.
---
In many settings it is important for one to be able to understand why a model
made a particular prediction. In NLP this often entails extracting snippets of
an input text `responsible for' corresponding model output; when such a snippet
comprises tokens that indeed informed the model's prediction, it is a faithful
explanation. In some settings, faithfulness may be critical to ensure
transparency. Lei et al. (2016) proposed a model to produce faithful rationales
for neural text classification by defining independent snippet extraction and
prediction modules. However, the discrete selection over input tokens performed
by this method complicates training, leading to high variance and requiring
careful hyperparameter tuning. We propose a simpler variant of this approach
that provides faithful explanations by construction. In our scheme, named
FRESH, arbitrary feature importance scores (e.g., gradients from a trained
model) are used to induce binary labels over token inputs, which an extractor
can be trained to predict. An independent classifier module is then trained
exclusively on snippets provided by the extractor; these snippets thus
constitute faithful explanations, even if the classifier is arbitrarily
complex. In both automatic and manual evaluations we find that variants of this
simple framework yield predictive performance superior to `end-to-end'
approaches, while being more general and easier to train. Code is available at
https://github.com/successar/FRESH