---
layout: publication
title: Residual Energy-based Models For Text
authors: Bakhtin et al.
conference: Journal of Machine Learning Research 21 (2020) 1-41
year: 2020
bibkey: bakhtin2020residual
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10188'}]
tags: [Training Techniques, Tools, Evaluation]
---
Current large-scale auto-regressive language models display impressive
fluency and can generate convincing text. In this work we start by asking the
question: Can the generations of these models be reliably distinguished from
real text by statistical discriminators? We find experimentally that the answer
is affirmative when we have access to the training data for the model, and
guardedly affirmative even if we do not.
  This suggests that the auto-regressive models can be improved by
incorporating the (globally normalized) discriminators into the generative
process. We give a formalism for this using the Energy-Based Model framework,
and show that it indeed improves the results of the generative models, measured
both in terms of perplexity and in terms of human evaluation.