---
layout: publication
title: Overview Of The TREC 2019 Deep Learning Track
authors: Nick Craswell, Bhaskar Mitra, Emine Yilmaz, Daniel Campos, Ellen M. Voorhees
conference: Arxiv
year: 2020
bibkey: craswell2020overview
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.07820'}]
tags: ["Evaluation"]
short_authors: Craswell et al.
---
The Deep Learning Track is a new track for TREC 2019, with the goal of
studying ad hoc ranking in a large data regime. It is the first track with
large human-labeled training sets, introducing two sets corresponding to two
tasks, each with rigorous TREC-style blind evaluation and reusable test sets.
The document retrieval task has a corpus of 3.2 million documents with 367
thousand training queries, for which we generate a reusable test set of 43
queries. The passage retrieval task has a corpus of 8.8 million passages with
503 thousand training queries, for which we generate a reusable test set of 43
queries. This year 15 groups submitted a total of 75 runs, using various
combinations of deep learning, transfer learning and traditional IR ranking
methods. Deep learning runs significantly outperformed traditional IR runs.
Possible explanations for this result are that we introduced large training
data and we included deep models trained on such data in our judging pools,
whereas some past studies did not have such training data or pooling.