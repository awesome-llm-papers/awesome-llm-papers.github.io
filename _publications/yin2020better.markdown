---
layout: publication
title: Better Sign Language Translation With Stmc-transformer
authors: Yin Kayo, Read Jesse
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2020
bibkey: yin2020better
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.00588'}]
tags: [Datasets, Training Techniques, COLING, Transformer, Model Architecture, SLT]
---
Sign Language Translation (SLT) first uses a Sign Language Recognition (SLR)
system to extract sign language glosses from videos. Then, a translation system
generates spoken language translations from the sign language glosses. This
paper focuses on the translation system and introduces the STMC-Transformer
which improves on the current state-of-the-art by over 5 and 7 BLEU
respectively on gloss-to-text and video-to-text translation of the
PHOENIX-Weather 2014T dataset. On the ASLG-PC12 corpus, we report an increase
of over 16 BLEU.
  We also demonstrate the problem in current methods that rely on gloss
supervision. The video-to-text translation of our STMC-Transformer outperforms
translation of GT glosses. This contradicts previous claims that GT gloss
translation acts as an upper bound for SLT performance and reveals that glosses
are an inefficient representation of sign language. For future SLT research, we
therefore suggest an end-to-end training of the recognition and translation
models, or using a different sign language annotation scheme.