---
layout: publication
title: Encoder Adaptation Of Dense Passage Retrieval For Open-domain Question Answering
authors: Li Minghan, Lin Jimmy
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2021
bibkey: li2021encoder
citations: 980
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.01599'}]
tags: [Fine Tuning, Datasets, Evaluation, EMNLP]
---
One key feature of dense passage retrievers (DPR) is the use of separate
question and passage encoder in a bi-encoder design. Previous work on
generalization of DPR mainly focus on testing both encoders in tandem on
out-of-distribution (OOD) question-answering (QA) tasks, which is also known as
domain adaptation. However, it is still unknown how DPR's individual
question/passage encoder affects generalization. Specifically, in this paper,
we want to know how an in-distribution (IND) question/passage encoder would
generalize if paired with an OOD passage/question encoder from another domain.
We refer to this challenge as \textit\{encoder adaptation\}. To answer this
question, we inspect different combinations of DPR's question and passage
encoder learned from five benchmark QA datasets on both in-domain and
out-of-domain questions. We find that the passage encoder has more influence on
the lower bound of generalization while the question encoder seems to affect
the upper bound in general. For example, applying an OOD passage encoder
usually hurts the retrieval accuracy while an OOD question encoder sometimes
even improves the accuracy.