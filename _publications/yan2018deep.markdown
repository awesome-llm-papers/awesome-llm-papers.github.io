---
layout: publication
title: A Deep Cascade Model For Multi-document Reading Comprehension
authors: Ming Yan, Jiangnan Xia, Chen Wu, Bin Bi, Zhongzhou Zhao, Ji Zhang, Luo Si,
  Rui Wang, Wei Wang, Haiqing Chen
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: yan2018deep
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.11374'}]
tags: ["AAAI"]
short_authors: Yan et al.
---
A fundamental trade-off between effectiveness and efficiency needs to be
balanced when designing an online question answering system. Effectiveness
comes from sophisticated functions such as extractive machine reading
comprehension (MRC), while efficiency is obtained from improvements in
preliminary retrieval components such as candidate document selection and
paragraph ranking. Given the complexity of the real-world multi-document MRC
scenario, it is difficult to jointly optimize both in an end-to-end system. To
address this problem, we develop a novel deep cascade learning model, which
progressively evolves from the document-level and paragraph-level ranking of
candidate texts to more precise answer extraction with machine reading
comprehension. Specifically, irrelevant documents and paragraphs are first
filtered out with simple functions for efficiency consideration. Then we
jointly train three modules on the remaining texts for better tracking the
answer: the document extraction, the paragraph extraction and the answer
extraction. Experiment results show that the proposed method outperforms the
previous state-of-the-art methods on two large-scale multi-document benchmark
datasets, i.e., TriviaQA and DuReader. In addition, our online system can
stably serve typical scenarios with millions of daily requests in less than
50ms.