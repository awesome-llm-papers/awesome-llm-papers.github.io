---
layout: publication
title: The Limitations Of Stylometry For Detecting Machine-generated Fake News
authors: Schuster et al.
conference: Computational Linguistics
year: 2019
bibkey: schuster2019limitations
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09805'}]
tags: [Datasets, Evaluation, TACL, ACL, Reinforcement Learning, Applications, NAACL,
  EACL, COLING]
---
Recent developments in neural language models (LMs) have raised concerns
about their potential misuse for automatically spreading misinformation. In
light of these concerns, several studies have proposed to detect
machine-generated fake news by capturing their stylistic differences from
human-written text. These approaches, broadly termed stylometry, have found
success in source attribution and misinformation detection in human-written
texts. However, in this work, we show that stylometry is limited against
machine-generated misinformation. While humans speak differently when trying to
deceive, LMs generate stylistically consistent text, regardless of underlying
motive. Thus, though stylometry can successfully prevent impersonation by
identifying text provenance, it fails to distinguish legitimate LM applications
from those that introduce false information. We create two benchmarks
demonstrating the stylistic similarity between malicious and legitimate uses of
LMs, employed in auto-completion and editing-assistance settings. Our findings
highlight the need for non-stylometry approaches in detecting machine-generated
misinformation, and open up the discussion on the desired evaluation
benchmarks.