---
layout: publication
title: 'Allennlp Interpret: A Framework For Explaining Predictions Of NLP Models'
authors: Eric Wallace, Jens Tuyls, Junlin Wang, Sanjay Subramanian, Matt Gardner,
  Sameer Singh
conference: 'Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP): System Demonstrations'
year: 2019
bibkey: wallace2019allennlp
citations: 129
additional_links: [{name: Code, url: 'https://allennlp.org/interpret'}, {name: Paper,
    url: 'https://arxiv.org/abs/1909.09251'}]
tags: ["EMNLP", "Tools"]
short_authors: Wallace et al.
---
Neural NLP models are increasingly accurate but are imperfect and
opaque---they break in counterintuitive ways and leave end users puzzled at
their behavior. Model interpretation methods ameliorate this opacity by
providing explanations for specific model predictions. Unfortunately, existing
interpretation codebases make it difficult to apply these methods to new models
and tasks, which hinders adoption for practitioners and burdens
interpretability researchers. We introduce AllenNLP Interpret, a flexible
framework for interpreting NLP models. The toolkit provides interpretation
primitives (e.g., input gradients) for any AllenNLP model and task, a suite of
built-in interpretation methods, and a library of front-end visualization
components. We demonstrate the toolkit's flexibility and utility by
implementing live demos for five interpretation methods (e.g., saliency maps
and adversarial attacks) on a variety of models and tasks (e.g., masked
language modeling using BERT and reading comprehension using BiDAF). These
demos, alongside our code and tutorials, are available at
https://allennlp.org/interpret .