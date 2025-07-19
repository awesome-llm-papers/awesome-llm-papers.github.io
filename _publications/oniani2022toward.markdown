---
layout: publication
title: Toward Improving Health Literacy In Patient Education Materials With Neural
  Machine Translation Models
authors: Oniani et al.
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: oniani2022toward
citations: 598
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.06723'}]
tags: [Model Architecture, Training Techniques, BERT, ACL, Transformer, RAG, Datasets,
  Alt]
---
Health literacy is the central focus of Healthy People 2030, the fifth
iteration of the U.S. national goals and objectives. People with low health
literacy usually have trouble understanding health information, following
post-visit instructions, and using prescriptions, which results in worse health
outcomes and serious health disparities. In this study, we propose to leverage
natural language processing techniques to improve health literacy in patient
education materials by automatically translating illiterate languages in a
given sentence. We scraped patient education materials from four online health
information websites: MedlinePlus.gov, Drugs.com, Mayoclinic.org and
Reddit.com. We trained and tested the state-of-the-art neural machine
translation (NMT) models on a silver standard training dataset and a gold
standard testing dataset, respectively. The experimental results showed that
the Bidirectional Long Short-Term Memory (BiLSTM) NMT model outperformed
Bidirectional Encoder Representations from Transformers (BERT)-based NMT
models. We also verified the effectiveness of NMT models in translating health
illiterate languages by comparing the ratio of health illiterate language in
the sentence. The proposed NMT models were able to identify the correct
complicated words and simplify into layman language while at the same time the
models suffer from sentence completeness, fluency, readability, and have
difficulty in translating certain medical terms.