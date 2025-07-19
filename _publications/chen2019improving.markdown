---
layout: publication
title: Improving End-to-end Sequential Recommendations With Intent-aware Diversification
authors: Chen et al.
conference: Proceedings of the 29th ACM International Conference on Information &amp;
  Knowledge Management
year: 2019
bibkey: chen2019improving
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10171'}]
tags: [Datasets, Training Techniques, CIKM, Evaluation]
---
Sequential Recommendation (SRs) that capture users' dynamic intents by
modeling user sequential behaviors can recommend closely accurate products to
users. Previous work on SRs is mostly focused on optimizing the recommendation
accuracy, often ignoring the recommendation diversity, even though it is an
important criterion for evaluating the recommendation performance. Most
existing methods for improving the diversity of recommendations are not ideally
applicable for SRs because they assume that user intents are static and rely on
post-processing the list of recommendations to promote diversity. We consider
both recommendation accuracy and diversity for SRs by proposing an end-to-end
neural model, called Intent-aware Diversified Sequential Recommendation (IDSR).
Specifically, we introduce an Implicit Intent Mining module (IIM) into SRs to
capture different user intents reflected in user behavior sequences. Then, we
design an Intent-aware Diversity Promoting (IDP) loss to supervise the learning
of the IIM module and force the model to take recommendation diversity into
consideration during training. Extensive experiments on two benchmark datasets
show that IDSR significantly outperforms state-of-the-art methods in terms of
recommendation diversity while yielding comparable or superior recommendation
accuracy.