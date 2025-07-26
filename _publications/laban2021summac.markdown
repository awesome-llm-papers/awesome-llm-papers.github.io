---
layout: publication
title: 'Summac: Re-visiting Nli-based Models For Inconsistency Detection In Summarization'
authors: Philippe Laban, Tobias Schnabel, Paul N. Bennett, Marti A. Hearst
conference: Transactions of the Association for Computational Linguistics
year: 2022
bibkey: laban2021summac
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.09525'}]
tags: ["Evaluation", "TACL"]
short_authors: Laban et al.
---
In the summarization domain, a key requirement for summaries is to be
factually consistent with the input document. Previous work has found that
natural language inference (NLI) models do not perform competitively when
applied to inconsistency detection. In this work, we revisit the use of NLI for
inconsistency detection, finding that past work suffered from a mismatch in
input granularity between NLI datasets (sentence-level), and inconsistency
detection (document level). We provide a highly effective and light-weight
method called SummaCConv that enables NLI models to be successfully used for
this task by segmenting documents into sentence units and aggregating scores
between pairs of sentences. On our newly introduced benchmark called SummaC
(Summary Consistency) consisting of six large inconsistency detection datasets,
SummaCConv obtains state-of-the-art results with a balanced accuracy of 74.4%,
a 5% point improvement compared to prior work. We make the models and datasets
available: https://github.com/tingofurro/summac