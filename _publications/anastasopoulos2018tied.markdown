---
layout: publication
title: Tied Multitask Learning For Neural Speech Translation
authors: Antonios Anastasopoulos, David Chiang
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: anastasopoulos2018tied
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.06655'}]
tags: ["NAACL"]
short_authors: Antonios Anastasopoulos, David Chiang
---
We explore multitask models for neural translation of speech, augmenting them
in order to reflect two intuitive notions. First, we introduce a model where
the second task decoder receives information from the decoder of the first
task, since higher-level intermediate representations should provide useful
information. Second, we apply regularization that encourages transitivity and
invertibility. We show that the application of these notions on jointly trained
models improves performance on the tasks of low-resource speech transcription
and translation. It also leads to better performance when using attention
information for word discovery over unsegmented input.