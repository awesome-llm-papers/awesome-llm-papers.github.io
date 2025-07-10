---
layout: publication
title: 'TIARA: Multi-grained Retrieval For Robust Question Answering Over Large Knowledge
  Bases'
authors: Yiheng Shu et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 15
bibkey: shu2022multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.12925'}]
tags: [ACL, RAG, Evaluation]
---
Pre-trained language models (PLMs) have shown their effectiveness in multiple
scenarios. However, KBQA remains challenging, especially regarding coverage and
generalization settings. This is due to two main factors: i) understanding the
semantics of both questions and relevant knowledge from the KB; ii) generating
executable logical forms with both semantic and syntactic correctness. In this
paper, we present a new KBQA model, TIARA, which addresses those issues by
applying multi-grained retrieval to help the PLM focus on the most relevant KB
contexts, viz., entities, exemplary logical forms, and schema items. Moreover,
constrained decoding is used to control the output space and reduce generation
errors. Experiments over important benchmarks demonstrate the effectiveness of
our approach. TIARA outperforms previous SOTA, including those using PLMs or
oracle entity annotations, by at least 4.1 and 1.1 F1 points on GrailQA and
WebQuestionsSP, respectively.