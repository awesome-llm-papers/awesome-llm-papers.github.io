---
layout: publication
title: Handling Divergent Reference Texts When Evaluating Table-to-text Generation
authors: Bhuwan Dhingra, Manaal Faruqui, Ankur Parikh, Ming-wei Chang, Dipanjan Das,
  William W. Cohen
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: dhingra2019handling
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01081'}]
tags: ["Datasets", "Evaluation"]
short_authors: Dhingra et al.
---
Automatically constructed datasets for generating text from semi-structured
data (tables), such as WikiBio, often contain reference texts that diverge from
the information in the corresponding semi-structured data. We show that metrics
which rely solely on the reference texts, such as BLEU and ROUGE, show poor
correlation with human judgments when those references diverge. We propose a
new metric, PARENT, which aligns n-grams from the reference and generated texts
to the semi-structured data before computing their precision and recall.
Through a large scale human evaluation study of table-to-text models for
WikiBio, we show that PARENT correlates with human judgments better than
existing text generation metrics. We also adapt and evaluate the information
extraction based evaluation proposed by Wiseman et al (2017), and show that
PARENT has comparable correlation to it, while being easier to use. We show
that PARENT is also applicable when the reference texts are elicited from
humans using the data from the WebNLG challenge.