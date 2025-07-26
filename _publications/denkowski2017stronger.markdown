---
layout: publication
title: Stronger Baselines For Trustable Results In Neural Machine Translation
authors: Michael Denkowski, Graham Neubig
conference: Proceedings of the First Workshop on Neural Machine Translation
year: 2017
bibkey: denkowski2017stronger
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.09733'}]
tags: ["Evaluation"]
short_authors: Michael Denkowski, Graham Neubig
---
Interest in neural machine translation has grown rapidly as its effectiveness
has been demonstrated across language and data scenarios. New research
regularly introduces architectural and algorithmic improvements that lead to
significant gains over "vanilla" NMT implementations. However, these new
techniques are rarely evaluated in the context of previously published
techniques, specifically those that are widely used in state-of-theart
production and shared-task systems. As a result, it is often difficult to
determine whether improvements from research will carry over to systems
deployed for real-world use. In this work, we recommend three specific methods
that are relatively easy to implement and result in much stronger experimental
systems. Beyond reporting significantly higher BLEU scores, we conduct an
in-depth analysis of where improvements originate and what inherent weaknesses
of basic NMT models are being addressed. We then compare the relative gains
afforded by several other techniques proposed in the literature when starting
with vanilla systems versus our stronger baselines, showing that experimental
conclusions may change depending on the baseline chosen. This indicates that
choosing a strong baseline is crucial for reporting reliable experimental
results.