---
layout: publication
title: 'Sequencer: Sequence-to-sequence Learning For End-to-end Program Repair'
authors: "Zimin Chen, Steve Kommrusch, Michele Tufano, Louis-no\xEBl Pouchet, Denys\
  \ Poshyvanyk, Martin Monperrus"
conference: IEEE Transactions on Software Engineering
year: 2019
bibkey: chen2018sequencer
citations: 343
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.01808'}]
tags: ["Datasets", "Evaluation"]
short_authors: Chen et al.
---
This paper presents a novel end-to-end approach to program repair based on
sequence-to-sequence learning. We devise, implement, and evaluate a system,
called SequenceR, for fixing bugs based on sequence-to-sequence learning on
source code. This approach uses the copy mechanism to overcome the unlimited
vocabulary problem that occurs with big code. Our system is data-driven; we
train it on 35,578 samples, carefully curated from commits to open-source
repositories. We evaluate it on 4,711 independent real bug fixes, as well on
the Defects4J benchmark used in program repair research. SequenceR is able to
perfectly predict the fixed line for 950/4711 testing samples, and find correct
patches for 14 bugs in Defects4J. It captures a wide range of repair operators
without any domain-specific top-down design.