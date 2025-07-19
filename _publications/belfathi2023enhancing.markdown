---
layout: publication
title: Enhancing Pre-trained Language Models With Sentence Position Embeddings For
  Rhetorical Roles Recognition In Legal Opinions
authors: Belfathi Anas, Hernandez Nicolas, Monceaux Laura
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2023
bibkey: belfathi2023enhancing
citations: 260
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.05276'}]
tags: [EMNLP, Attention Mechanism, BERT, Model Architecture, Datasets]
---
The legal domain is a vast and complex field that involves a considerable
amount of text analysis, including laws, legal arguments, and legal opinions.
Legal practitioners must analyze these texts to understand legal cases,
research legal precedents, and prepare legal documents. The size of legal
opinions continues to grow, making it increasingly challenging to develop a
model that can accurately predict the rhetorical roles of legal opinions given
their complexity and diversity. In this research paper, we propose a novel
model architecture for automatically predicting rhetorical roles using
pre-trained language models (PLMs) enhanced with knowledge of sentence position
information within a document. Based on an annotated corpus from the
LegalEval@SemEval2023 competition, we demonstrate that our approach requires
fewer parameters, resulting in lower computational costs when compared to
complex architectures employing a hierarchical model in a global-context, yet
it achieves great performance. Moreover, we show that adding more attention to
a hierarchical model based only on BERT in the local-context, along with
incorporating sentence position information, enhances the results.