---
layout: publication
title: Learning A Neural Semantic Parser From User Feedback
authors: Iyer et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: iyer2017learning
citations: 324
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.08760'}]
tags: [ACL, Tools]
---
We present an approach to rapidly and easily build natural language
interfaces to databases for new domains, whose performance improves over time
based on user feedback, and requires minimal intervention. To achieve this, we
adapt neural sequence models to map utterances directly to SQL with its full
expressivity, bypassing any intermediate meaning representations. These models
are immediately deployed online to solicit feedback from real users to flag
incorrect queries. Finally, the popularity of SQL facilitates gathering
annotations for incorrect predictions using the crowd, which is directly used
to improve our models. This complete feedback loop, without intermediate
representations or database specific engineering, opens up new ways of building
high quality semantic parsers. Experiments suggest that this approach can be
deployed quickly for any new target domain, as we show by learning a semantic
parser for an online academic database from scratch.