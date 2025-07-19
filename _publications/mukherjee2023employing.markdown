---
layout: publication
title: Employing Deep Learning And Structured Information Retrieval To Answer Clarification
  Questions On Bug Reports
authors: Mukherjee Usmi, Rahman Mohammad Masudur
conference: 2015 30th IEEE/ACM International Conference on Automated Software Engineering
  (ASE)
year: 2023
bibkey: mukherjee2023employing
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.12494'}]
tags: [Prompting, LLM For Code, Evaluation, LLM for Code, RAG]
---
Software bug reports reported on bug-tracking systems often lack crucial
information for the developers to promptly resolve them, costing companies
billions of dollars. There has been significant research on effectively
eliciting information from bug reporters in bug tracking systems using
different templates that bug reporters need to use. However, the need for
asking follow-up questions persists. Recent studies propose techniques to
suggest these follow-up questions to help developers obtain the missing
details, but there has been little research on answering these follow up
questions, which are often unanswered. In this paper, we propose a novel
approach that uses CodeT5 in combination with Lucene, an information retrieval
technique that leverages the relevance of different bug reports, their
components, and follow-up questions to recommend answers. These top-performing
answers, along with their bug report, serve as additional context apart from
the deficient bug report to the deep learning model for generating an answer.
We evaluate our recommended answers with the manually annotated answers using
similarity metrics like Normalized Smooth BLEU Score, METEOR, Word Mover's
Distance, and Semantic Similarity. We achieve a BLEU Score of up to 34 and
Semantic Similarity of up to 64 which shows that the answers generated are
understandable and good according to Google's standard and can outperform
multiple baselines.