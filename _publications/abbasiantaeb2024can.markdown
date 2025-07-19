---
layout: publication
title: Can We Use Large Language Models To Fill Relevance Judgment Holes?
authors: Abbasiantaeb et al.
conference: Proceedings of the 2023 ACM SIGIR International Conference on Theory of
  Information Retrieval
year: 2024
bibkey: abbasiantaeb2024can
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.05600'}]
tags: [RAG, Training Techniques, Prompting, SIGIR, Fine Tuning]
---
Incomplete relevance judgments limit the re-usability of test collections.
When new systems are compared against previous systems used to build the pool
of judged documents, they often do so at a disadvantage due to the ``holes'' in
test collection (i.e., pockets of un-assessed documents returned by the new
system). In this paper, we take initial steps towards extending existing test
collections by employing Large Language Models (LLM) to fill the holes by
leveraging and grounding the method using existing human judgments. We explore
this problem in the context of Conversational Search using TREC iKAT, where
information needs are highly dynamic and the responses (and, the results
retrieved) are much more varied (leaving bigger holes). While previous work has
shown that automatic judgments from LLMs result in highly correlated rankings,
we find substantially lower correlates when human plus automatic judgments are
used (regardless of LLM, one/two/few shot, or fine-tuned). We further find
that, depending on the LLM employed, new runs will be highly favored (or
penalized), and this effect is magnified proportionally to the size of the
holes. Instead, one should generate the LLM annotations on the whole document
pool to achieve more consistent rankings with human-generated labels. Future
work is required to prompt engineering and fine-tuning LLMs to reflect and
represent the human annotations, in order to ground and align the models, such
that they are more fit for purpose.