---
layout: publication
title: 'Questeval: Summarization Asks For Fact-based Evaluation'
authors: Thomas Scialom, Paul-alexis Dray, Patrick Gallinari, Sylvain Lamprier, Benjamin
  Piwowarski, Jacopo Staiano, Alex Wang
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: scialom2021questeval
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.12693'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Scialom et al.
---
Summarization evaluation remains an open research problem: current metrics
such as ROUGE are known to be limited and to correlate poorly with human
judgments. To alleviate this issue, recent work has proposed evaluation metrics
which rely on question answering models to assess whether a summary contains
all the relevant information in its source document. Though promising, the
proposed approaches have so far failed to correlate better than ROUGE with
human judgments.
  In this paper, we extend previous approaches and propose a unified framework,
named QuestEval. In contrast to established metrics such as ROUGE or BERTScore,
QuestEval does not require any ground-truth reference. Nonetheless, QuestEval
substantially improves the correlation with human judgments over four
evaluation dimensions (consistency, coherence, fluency, and relevance), as
shown in the extensive experiments we report.