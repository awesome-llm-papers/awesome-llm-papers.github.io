---
layout: publication
title: Learning Recurrent Span Representations For Extractive Question Answering
authors: Kenton Lee, Shimi Salant, Tom Kwiatkowski, Ankur Parikh, Dipanjan Das, Jonathan
  Berant
conference: Arxiv
year: 2016
bibkey: lee2016learning
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.01436'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Lee et al.
---
The reading comprehension task, that asks questions about a given evidence
document, is a central problem in natural language understanding. Recent
formulations of this task have typically focused on answer selection from a set
of candidates pre-defined manually or through the use of an external NLP
pipeline. However, Rajpurkar et al. (2016) recently released the SQuAD dataset
in which the answers can be arbitrary strings from the supplied text. In this
paper, we focus on this answer extraction task, presenting a novel model
architecture that efficiently builds fixed length representations of all spans
in the evidence document with a recurrent network. We show that scoring
explicit span representations significantly improves performance over other
approaches that factor the prediction into separate predictions about words or
start and end markers. Our approach improves upon the best published results of
Wang & Jiang (2016) by 5% and decreases the error of Rajpurkar et al.'s
baseline by > 50%.