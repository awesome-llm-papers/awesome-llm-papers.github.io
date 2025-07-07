---
layout: publication
title: Ranking Paragraphs For Improving Answer Recall In Open-domain Question Answering
authors: Jinhyuk Lee, Seongjun Yun, Hyunjae Kim, Miyoung Ko, Jaewoo Kang
conference: Arxiv
year: 2018
citations: 34
bibkey: lee2018ranking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.00494'}]
tags: [RAG]
---
Recently, open-domain question answering (QA) has been combined with machine
comprehension models to find answers in a large knowledge source. As
open-domain QA requires retrieving relevant documents from text corpora to
answer questions, its performance largely depends on the performance of
document retrievers. However, since traditional information retrieval systems
are not effective in obtaining documents with a high probability of containing
answers, they lower the performance of QA systems. Simply extracting more
documents increases the number of irrelevant documents, which also degrades the
performance of QA systems. In this paper, we introduce Paragraph Ranker which
ranks paragraphs of retrieved documents for a higher answer recall with less
noise. We show that ranking paragraphs and aggregating answers using Paragraph
Ranker improves performance of open-domain QA pipeline on the four open-domain
QA datasets by 7.8% on average.