---
layout: publication
title: Classical Structured Prediction Losses For Sequence To Sequence Learning
authors: Sergey Edunov, Myle Ott, Michael Auli, David Grangier, Marc'aurelio Ranzato
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: edunov2017classical
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.04956'}]
tags: ["Model Architecture", "NAACL", "Training Techniques"]
short_authors: Edunov et al.
---
There has been much recent work on training neural attention models at the
sequence-level using either reinforcement learning-style methods or by
optimizing the beam. In this paper, we survey a range of classical objective
functions that have been widely used to train linear models for structured
prediction and apply them to neural sequence to sequence models. Our
experiments show that these losses can perform surprisingly well by slightly
outperforming beam search optimization in a like for like setup. We also report
new state of the art results on both IWSLT'14 German-English translation as
well as Gigaword abstractive summarization. On the larger WMT'14 English-French
translation task, sequence-level training achieves 41.5 BLEU which is on par
with the state of the art.