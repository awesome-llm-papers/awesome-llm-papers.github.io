---
layout: publication
title: Quantifying Memorization Across Neural Language Models
authors: Nicholas Carlini et al.
conference: Arxiv
year: 2022
citations: 119
bibkey: carlini2022quantifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.07646'}]
tags: [Ethics and Bias, Fairness, Bias Mitigation, Prompting, Training Techniques]
---
Large language models (LMs) have been shown to memorize parts of their
training data, and when prompted appropriately, they will emit the memorized
training data verbatim. This is undesirable because memorization violates
privacy (exposing user data), degrades utility (repeated easy-to-memorize text
is often low quality), and hurts fairness (some texts are memorized over
others).
  We describe three log-linear relationships that quantify the degree to which
LMs emit memorized training data. Memorization significantly grows as we
increase (1) the capacity of a model, (2) the number of times an example has
been duplicated, and (3) the number of tokens of context used to prompt the
model. Surprisingly, we find the situation becomes more complicated when
generalizing these results across model families. On the whole, we find that
memorization in LMs is more prevalent than previously believed and will likely
get worse as models continues to scale, at least without active mitigations.