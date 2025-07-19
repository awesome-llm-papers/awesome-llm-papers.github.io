---
layout: publication
title: 'Trustworthy Machine Learning Via Memorization And The Granular Long-tail:
  A Survey On Interactions, Tradeoffs, And Beyond'
authors: Li et al.
conference: Proceedings of the 52nd Annual ACM SIGACT Symposium on Theory of Computing
year: 2025
bibkey: li2025trustworthy
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.07501'}]
tags: [RAG, Fairness, Training Techniques, Attention Mechanism, Bias Mitigation, Tools,
  Ethics And Bias, Model Architecture, Survey Paper, Reinforcement Learning, Security]
---
The role of memorization in machine learning (ML) has garnered significant
attention, particularly as modern models are empirically observed to memorize
fragments of training data. Previous theoretical analyses, such as Feldman's
seminal work, attribute memorization to the prevalence of long-tail
distributions in training data, proving it unavoidable for samples that lie in
the tail of the distribution. However, the intersection of memorization and
trustworthy ML research reveals critical gaps. While prior research in
memorization in trustworthy ML has solely focused on class imbalance, recent
work starts to differentiate class-level rarity from atypical samples, which
are valid and rare intra-class instances. However, a critical research gap
remains: current frameworks conflate atypical samples with noisy and erroneous
data, neglecting their divergent impacts on fairness, robustness, and privacy.
In this work, we conduct a thorough survey of existing research and their
findings on trustworthy ML and the role of memorization. More and beyond, we
identify and highlight uncharted gaps and propose new revenues in this research
direction. Since existing theoretical and empirical analyses lack the nuances
to disentangle memorization's duality as both a necessity and a liability, we
formalize three-level long-tail granularity - class imbalance, atypicality, and
noise - to reveal how current frameworks misapply these levels, perpetuating
flawed solutions. By systematizing this granularity, we draw a roadmap for
future research. Trustworthy ML must reconcile the nuanced trade-offs between
memorizing atypicality for fairness assurance and suppressing noise for
robustness and privacy guarantee. Redefining memorization via this granularity
reshapes the theoretical foundation for trustworthy ML, and further affords an
empirical prerequisite for models that align performance with societal trust.