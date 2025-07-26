---
layout: publication
title: Neural Arabic Question Answering
authors: Hussein Mozannar, Karl El Hajal, Elie Maamary, Hazem Hajj
conference: Proceedings of the Fourth Arabic Natural Language Processing Workshop
year: 2019
bibkey: mozannar2019neural
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.05394'}]
tags: ["Datasets", "Model Architecture", "Retrieval Systems"]
short_authors: Mozannar et al.
---
This paper tackles the problem of open domain factual Arabic question
answering (QA) using Wikipedia as our knowledge source. This constrains the
answer of any question to be a span of text in Wikipedia. Open domain QA for
Arabic entails three challenges: annotated QA datasets in Arabic, large scale
efficient information retrieval and machine reading comprehension. To deal with
the lack of Arabic QA datasets we present the Arabic Reading Comprehension
Dataset (ARCD) composed of 1,395 questions posed by crowdworkers on Wikipedia
articles, and a machine translation of the Stanford Question Answering Dataset
(Arabic-SQuAD). Our system for open domain question answering in Arabic (SOQAL)
is based on two components: (1) a document retriever using a hierarchical
TF-IDF approach and (2) a neural reading comprehension model using the
pre-trained bi-directional transformer BERT. Our experiments on ARCD indicate
the effectiveness of our approach with our BERT-based reader achieving a 61.3
F1 score, and our open domain system SOQAL achieving a 27.6 F1 score.