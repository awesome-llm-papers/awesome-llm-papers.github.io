---
layout: publication
title: 'Seeing Like An AI: How Llms Apply (and Misapply) Wikipedia Neutrality Norms'
authors: Ashkinaze et al.
conference: Proceedings of the ACM on Human-Computer Interaction
year: 2024
bibkey: ashkinaze2024seeing
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.04183'}]
tags: [Datasets, Ethics And Bias]
---
Large language models (LLMs) are trained on broad corpora and then used in
communities with specialized norms. Is providing LLMs with community rules
enough for models to follow these norms? We evaluate LLMs' capacity to detect
(Task 1) and correct (Task 2) biased Wikipedia edits according to Wikipedia's
Neutral Point of View (NPOV) policy. LLMs struggled with bias detection,
achieving only 64% accuracy on a balanced dataset. Models exhibited contrasting
biases (some under- and others over-predicted bias), suggesting distinct priors
about neutrality. LLMs performed better at generation, removing 79% of words
removed by Wikipedia editors. However, LLMs made additional changes beyond
Wikipedia editors' simpler neutralizations, resulting in high-recall but
low-precision editing. Interestingly, crowdworkers rated AI rewrites as more
neutral (70%) and fluent (61%) than Wikipedia-editor rewrites. Qualitative
analysis found LLMs sometimes applied NPOV more comprehensively than Wikipedia
editors but often made extraneous non-NPOV-related changes (such as grammar).
LLMs may apply rules in ways that resonate with the public but diverge from
community experts. While potentially effective for generation, LLMs may reduce
editor agency and increase moderation workload (e.g., verifying additions).
Even when rules are easy to articulate, having LLMs apply them like community
members may still be difficult.