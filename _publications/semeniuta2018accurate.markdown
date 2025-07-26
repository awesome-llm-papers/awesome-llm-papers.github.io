---
layout: publication
title: On Accurate Evaluation Of Gans For Language Generation
authors: Stanislau Semeniuta, Aliaksei Severyn, Sylvain Gelly
conference: Arxiv
year: 2018
bibkey: semeniuta2018accurate
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.04936'}]
tags: ["Evaluation"]
short_authors: Stanislau Semeniuta, Aliaksei Severyn, Sylvain Gelly
---
Generative Adversarial Networks (GANs) are a promising approach to language
generation. The latest works introducing novel GAN models for language
generation use n-gram based metrics for evaluation and only report single
scores of the best run. In this paper, we argue that this often misrepresents
the true picture and does not tell the full story, as GAN models can be
extremely sensitive to the random initialization and small deviations from the
best hyperparameter choice. In particular, we demonstrate that the previously
used BLEU score is not sensitive to semantic deterioration of generated texts
and propose alternative metrics that better capture the quality and diversity
of the generated samples. We also conduct a set of experiments comparing a
number of GAN models for text with a conventional Language Model (LM) and find
that neither of the considered models performs convincingly better than the LM.