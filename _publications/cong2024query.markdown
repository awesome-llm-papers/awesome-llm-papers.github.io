---
layout: publication
title: Query Optimization For Parametric Knowledge Refinement In Retrieval-augmented
  Large Language Models
authors: Cong et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: cong2024query
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.07820'}]
tags: [RAG, EMNLP, Distillation, Tools, Evaluation, Efficiency And Optimization, Datasets]
---
We introduce the Extract-Refine-Retrieve-Read (ERRR) framework, a novel
approach designed to bridge the pre-retrieval information gap in
Retrieval-Augmented Generation (RAG) systems through query optimization
tailored to meet the specific knowledge requirements of Large Language Models
(LLMs). Unlike conventional query optimization techniques used in RAG, the ERRR
framework begins by extracting parametric knowledge from LLMs, followed by
using a specialized query optimizer for refining these queries. This process
ensures the retrieval of only the most pertinent information essential for
generating accurate responses. Moreover, to enhance flexibility and reduce
computational costs, we propose a trainable scheme for our pipeline that
utilizes a smaller, tunable model as the query optimizer, which is refined
through knowledge distillation from a larger teacher model. Our evaluations on
various question-answering (QA) datasets and with different retrieval systems
show that ERRR consistently outperforms existing baselines, proving to be a
versatile and cost-effective module for improving the utility and accuracy of
RAG systems.