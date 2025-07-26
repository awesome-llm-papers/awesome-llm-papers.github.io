---
layout: publication
title: 'Sign Language Transformers: Joint End-to-end Sign Language Recognition And
  Translation'
authors: Necati Cihan Camgoz, Oscar Koller, Simon Hadfield, Richard Bowden
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: camgoz2020sign
citations: 341
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.13830'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Camgoz et al.
---
Prior work on Sign Language Translation has shown that having a mid-level
sign gloss representation (effectively recognizing the individual signs)
improves the translation performance drastically. In fact, the current
state-of-the-art in translation requires gloss level tokenization in order to
work. We introduce a novel transformer based architecture that jointly learns
Continuous Sign Language Recognition and Translation while being trainable in
an end-to-end manner. This is achieved by using a Connectionist Temporal
Classification (CTC) loss to bind the recognition and translation problems into
a single unified architecture. This joint approach does not require any
ground-truth timing information, simultaneously solving two co-dependant
sequence-to-sequence learning problems and leads to significant performance
gains.
  We evaluate the recognition and translation performances of our approaches on
the challenging RWTH-PHOENIX-Weather-2014T (PHOENIX14T) dataset. We report
state-of-the-art sign language recognition and translation results achieved by
our Sign Language Transformers. Our translation networks outperform both sign
video to spoken language and gloss to spoken language translation models, in
some cases more than doubling the performance (9.58 vs. 21.80 BLEU-4 Score). We
also share new baseline translation results using transformer networks for
several other text-to-text sign language translation tasks.