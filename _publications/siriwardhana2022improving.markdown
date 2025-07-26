---
layout: publication
title: Improving The Domain Adaptation Of Retrieval Augmented Generation (RAG) Models
  For Open Domain Question Answering
authors: Shamane Siriwardhana, Rivindu Weerasekera, Elliott Wen, Tharindu Kaluarachchi,
  Rajib Rana, Suranga Nanayakkara
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: siriwardhana2022improving
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.02627'}]
tags: ["RAG", "Retrieval Systems", "TACL"]
short_authors: Siriwardhana et al.
---
Retrieval Augment Generation (RAG) is a recent advancement in Open-Domain
Question Answering (ODQA). RAG has only been trained and explored with a
Wikipedia-based external knowledge base and is not optimized for use in other
specialized domains such as healthcare and news. In this paper, we evaluate the
impact of joint training of the retriever and generator components of RAG for
the task of domain adaptation in ODQA. We propose \textit\{RAG-end2end\}, an
extension to RAG, that can adapt to a domain-specific knowledge base by
updating all components of the external knowledge base during training. In
addition, we introduce an auxiliary training signal to inject more
domain-specific knowledge. This auxiliary signal forces \textit\{RAG-end2end\} to
reconstruct a given sentence by accessing the relevant information from the
external knowledge base. Our novel contribution is unlike RAG, RAG-end2end does
joint training of the retriever and generator for the end QA task and domain
adaptation. We evaluate our approach with datasets from three domains:
COVID-19, News, and Conversations, and achieve significant performance
improvements compared to the original RAG model. Our work has been open-sourced
through the Huggingface Transformers library, attesting to our work's
credibility and technical consistency.