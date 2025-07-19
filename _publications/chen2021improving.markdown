---
layout: publication
title: Improving Faithfulness In Abstractive Summarization With Contrast Candidate
  Generation And Selection
authors: Chen et al.
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: chen2021improving
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.09061'}]
tags: [ACL, Alt, NAACL]
---
Despite significant progress in neural abstractive summarization, recent
studies have shown that the current models are prone to generating summaries
that are unfaithful to the original context. To address the issue, we study
contrast candidate generation and selection as a model-agnostic post-processing
technique to correct the extrinsic hallucinations (i.e. information not present
in the source text) in unfaithful summaries. We learn a discriminative
correction model by generating alternative candidate summaries where named
entities and quantities in the generated summary are replaced with ones with
compatible semantic types from the source document. This model is then used to
select the best candidate as the final output summary. Our experiments and
analysis across a number of neural summarization systems show that our proposed
method is effective in identifying and correcting extrinsic hallucinations. We
analyze the typical hallucination phenomenon by different types of neural
summarization systems, in hope to provide insights for future work on the
direction.