---
layout: publication
title: Coreference Reasoning In Machine Reading Comprehension
authors: Mingzhu Wu, Nafise Sadat Moosavi, Dan Roth, Iryna Gurevych
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wu2020coreference
citations: 155
additional_links: [{name: Code, url: 'https://github.com/UKPLab/coref-reasoning-in-qa'},
  {name: Paper, url: 'https://arxiv.org/abs/2012.15573'}]
tags: ["Datasets", "Evaluation", "Has Code", "Training Techniques"]
short_authors: Wu et al.
---
Coreference resolution is essential for natural language understanding and
has been long studied in NLP. In recent years, as the format of Question
Answering (QA) became a standard for machine reading comprehension (MRC), there
have been data collection efforts, e.g., Dasigi et al. (2019), that attempt to
evaluate the ability of MRC models to reason about coreference. However, as we
show, coreference reasoning in MRC is a greater challenge than earlier thought;
MRC datasets do not reflect the natural distribution and, consequently, the
challenges of coreference reasoning. Specifically, success on these datasets
does not reflect a model's proficiency in coreference reasoning. We propose a
methodology for creating MRC datasets that better reflect the challenges of
coreference reasoning and use it to create a sample evaluation set. The results
on our dataset show that state-of-the-art models still struggle with these
phenomena. Furthermore, we develop an effective way to use naturally occurring
coreference phenomena from existing coreference resolution datasets when
training MRC models. This allows us to show an improvement in the coreference
reasoning abilities of state-of-the-art models. The code and the resulting
dataset are available at https://github.com/UKPLab/coref-reasoning-in-qa.