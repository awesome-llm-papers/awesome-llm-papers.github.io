---
layout: publication
title: 'Neural Belief Tracker: Data-driven Dialogue State Tracking'
authors: "Nikola Mrk\u0161i\u0107, Diarmuid \xD3 S\xE9aghdha, Tsung-hsien Wen, Blaise\
  \ Thomson, Steve Young"
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: "mrk\u0161i\u01072016neural"
citations: 499
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.03777'}]
tags: ["Evaluation", "Tools"]
short_authors: "Mrk\u0161i\u0107 et al."
---
One of the core components of modern spoken dialogue systems is the belief
tracker, which estimates the user's goal at every step of the dialogue.
However, most current approaches have difficulty scaling to larger, more
complex dialogue domains. This is due to their dependency on either: a) Spoken
Language Understanding models that require large amounts of annotated training
data; or b) hand-crafted lexicons for capturing some of the linguistic
variation in users' language. We propose a novel Neural Belief Tracking (NBT)
framework which overcomes these problems by building on recent advances in
representation learning. NBT models reason over pre-trained word vectors,
learning to compose them into distributed representations of user utterances
and dialogue context. Our evaluation on two datasets shows that this approach
surpasses past limitations, matching the performance of state-of-the-art models
which rely on hand-crafted semantic lexicons and outperforming them when such
lexicons are not provided.