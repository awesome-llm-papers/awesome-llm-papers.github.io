---
layout: publication
title: 'HELP: A Dataset For Identifying Shortcomings Of Neural Models In Monotonicity
  Reasoning'
authors: Yanaka et al.
conference: Proceedings of the Eighth Joint Conference on Lexical and Computational
  Semantics (*SEM 2019)
year: 2019
bibkey: yanaka2019help
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.12166'}]
tags: [Training Techniques, Evaluation, Model Architecture, Datasets, TACL]
---
Large crowdsourced datasets are widely used for training and evaluating
neural models on natural language inference (NLI). Despite these efforts,
neural models have a hard time capturing logical inferences, including those
licensed by phrase replacements, so-called monotonicity reasoning. Since no
large dataset has been developed for monotonicity reasoning, it is still
unclear whether the main obstacle is the size of datasets or the model
architectures themselves. To investigate this issue, we introduce a new
dataset, called HELP, for handling entailments with lexical and logical
phenomena. We add it to training data for the state-of-the-art neural models
and evaluate them on test sets for monotonicity phenomena. The results showed
that our data augmentation improved the overall accuracy. We also find that the
improvement is better on monotonicity inferences with lexical replacements than
on downward inferences with disjunction and modification. This suggests that
some types of inferences can be improved by our data augmentation while others
are immune to it.