---
layout: publication
title: 'Pullnet: Open Domain Question Answering With Iterative Retrieval On Knowledge
  Bases And Text'
authors: Haitian Sun, Tania Bedrax-weiss, William W. Cohen
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: sun2019pullnet
citations: 280
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09537'}]
tags: ["EMNLP"]
short_authors: Haitian Sun, Tania Bedrax-weiss, William W. Cohen
---
We consider open-domain queston answering (QA) where answers are drawn from
either a corpus, a knowledge base (KB), or a combination of both of these. We
focus on a setting in which a corpus is supplemented with a large but
incomplete KB, and on questions that require non-trivial (e.g., ``multi-hop'')
reasoning. We describe PullNet, an integrated framework for (1) learning what
to retrieve (from the KB and/or corpus) and (2) reasoning with this
heterogeneous information to find the best answer. PullNet uses an \{iterative\}
process to construct a question-specific subgraph that contains information
relevant to the question. In each iteration, a graph convolutional network
(graph CNN) is used to identify subgraph nodes that should be expanded using
retrieval (or ``pull'') operations on the corpus and/or KB. After the subgraph
is complete, a similar graph CNN is used to extract the answer from the
subgraph. This retrieve-and-reason process allows us to answer multi-hop
questions using large KBs and corpora. PullNet is weakly supervised, requiring
question-answer pairs but not gold inference paths. Experimentally PullNet
improves over the prior state-of-the art, and in the setting where a corpus is
used with incomplete KB these improvements are often dramatic. PullNet is also
often superior to prior systems in a KB-only setting or a text-only setting.