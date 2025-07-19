---
layout: publication
title: The Gaps Between Pre-train And Downstream Settings In Bias Evaluation And Debiasing
authors: Kaneko Masahiro, Bollegala Danushka, Baldwin Timothy
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2024
bibkey: kaneko2024gaps
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.08511'}]
tags: [Ethics And Bias, Prompting, Training Techniques, Fine Tuning, Evaluation, ACL,
  In Context Learning, Datasets]
---
The output tendencies of Pre-trained Language Models (PLM) vary markedly
before and after Fine-Tuning (FT) due to the updates to the model parameters.
These divergences in output tendencies result in a gap in the social biases of
PLMs. For example, there exits a low correlation between intrinsic bias scores
of a PLM and its extrinsic bias scores under FT-based debiasing methods.
Additionally, applying FT-based debiasing methods to a PLM leads to a decline
in performance in downstream tasks. On the other hand, PLMs trained on large
datasets can learn without parameter updates via In-Context Learning (ICL)
using prompts. ICL induces smaller changes to PLMs compared to FT-based
debiasing methods. Therefore, we hypothesize that the gap observed in
pre-trained and FT models does not hold true for debiasing methods that use
ICL. In this study, we demonstrate that ICL-based debiasing methods show a
higher correlation between intrinsic and extrinsic bias scores compared to
FT-based methods. Moreover, the performance degradation due to debiasing is
also lower in the ICL case compared to that in the FT case.