---
layout: publication
title: 'Kagnet: Knowledge-aware Graph Networks For Commonsense Reasoning'
authors: Bill Yuchen Lin, Xinyue Chen, Jamin Chen, Xiang Ren
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: lin2019kagnet
citations: 460
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02151'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Lin et al.
---
Commonsense reasoning aims to empower machines with the human ability to make
presumptions about ordinary situations in our daily life. In this paper, we
propose a textual inference framework for answering commonsense questions,
which effectively utilizes external, structured commonsense knowledge graphs to
perform explainable inferences. The framework first grounds a question-answer
pair from the semantic space to the knowledge-based symbolic space as a schema
graph, a related sub-graph of external knowledge graphs. It represents schema
graphs with a novel knowledge-aware graph network module named KagNet, and
finally scores answers with graph representations. Our model is based on graph
convolutional networks and LSTMs, with a hierarchical path-based attention
mechanism. The intermediate attention scores make it transparent and
interpretable, which thus produce trustworthy inferences. Using ConceptNet as
the only external resource for Bert-based models, we achieved state-of-the-art
performance on the CommonsenseQA, a large-scale dataset for commonsense
reasoning.