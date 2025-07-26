---
layout: publication
title: 'FUDGE: Controlled Text Generation With Future Discriminators'
authors: Kevin Yang, Dan Klein
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: yang2021fudge
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.05218'}]
tags: ["NAACL"]
short_authors: Kevin Yang, Dan Klein
---
We propose Future Discriminators for Generation (FUDGE), a flexible and
modular method for controlled text generation. Given a pre-existing model G for
generating text from a distribution of interest, FUDGE enables conditioning on
a desired attribute a (for example, formality) while requiring access only to
G's output logits. FUDGE learns an attribute predictor operating on a partial
sequence, and uses this predictor's outputs to adjust G's original
probabilities. We show that FUDGE models terms corresponding to a Bayesian
decomposition of the conditional distribution of G given attribute a. Moreover,
FUDGE can easily compose predictors for multiple desired attributes. We
evaluate FUDGE on three tasks -- couplet completion in poetry, topic control in
language generation, and formality change in machine translation -- and observe
gains in all three tasks.