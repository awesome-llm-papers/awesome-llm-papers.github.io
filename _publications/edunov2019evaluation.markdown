---
layout: publication
title: On The Evaluation Of Machine Translation Systems Trained With Back-translation
authors: Sergey Edunov, Myle Ott, Marc'aurelio Ranzato, Michael Auli
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: edunov2019evaluation
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05204'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Edunov et al.
---
Back-translation is a widely used data augmentation technique which leverages
target monolingual data. However, its effectiveness has been challenged since
automatic metrics such as BLEU only show significant improvements for test
examples where the source itself is a translation, or translationese. This is
believed to be due to translationese inputs better matching the back-translated
training data. In this work, we show that this conjecture is not empirically
supported and that back-translation improves translation quality of both
naturally occurring text as well as translationese according to professional
human translators. We provide empirical evidence to support the view that
back-translation is preferred by humans because it produces more fluent
outputs. BLEU cannot capture human preferences because references are
translationese when source sentences are natural text. We recommend
complementing BLEU with a language model score to measure fluency.