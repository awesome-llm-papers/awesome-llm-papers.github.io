---
layout: publication
title: Harvesting Paragraph-level Question-answer Pairs From Wikipedia
authors: Xinya Du, Claire Cardie
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: du2018harvesting
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.05942'}]
tags: ["Retrieval Systems"]
short_authors: Xinya Du, Claire Cardie
---
We study the task of generating from Wikipedia articles question-answer pairs
that cover content beyond a single sentence. We propose a neural network
approach that incorporates coreference knowledge via a novel gating mechanism.
Compared to models that only take into account sentence-level information
(Heilman and Smith, 2010; Du et al., 2017; Zhou et al., 2017), we find that the
linguistic knowledge introduced by the coreference representation aids question
generation significantly, producing models that outperform the current
state-of-the-art. We apply our system (composed of an answer span extraction
system and the passage-level QG system) to the 10,000 top-ranking Wikipedia
articles and create a corpus of over one million question-answer pairs. We also
provide a qualitative analysis for this large-scale generated corpus from
Wikipedia.